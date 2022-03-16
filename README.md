# rushi.html
mywebsite
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rushikesh</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Baloo+Bhai+2:wght@600&family=Indie+Flower&family=Press+Start+2P&family=Shizuru&display=swap"
        rel="stylesheet">
</head>
<style>
    body {
        background-color:black;
        background-image: url(https://cdn.pixabay.com/photo/2018/06/17/08/40/hacker-3480124_960_720.jpg) no-repeat center center/cover;
        margin: 0px;
        padding: 0px;
        font-family: 'Baloo Bhai 2', cursive;
        height: 1050px;
    }

    /* left box for buttons  */
    .left {
        /* border: 2px solid red; */
        display: inline-block;
        color: aliceblue;
        position: absolute;
        left: 34px;
        top: 25px;

    }

    .left img {
        width: 110px;

    }

    .left div {
        text-align: center;
        font-size: 25px;
        color: whitesmoke;
    }
    .senter img{
        /* border: 2px solid red; */
        width: 60px;
        position: absolute;
        left: 750px;
        top: 0px;
    }

    /* mid box for buttons  */
    .mid {
        border: 2px solid rgb(245, 245, 243);
        border-radius: 30px;
        text-decoration: none;
        color: aliceblue;
        margin: 200px 460px;
        display: block;
        width: 40%;
    }

    .navbar {
        display: inline-block;
    }

    .navbar li {
        display: inline-block;
        color: aliceblue;
        font-size: 25px;
    }

    .navbar li a {
        color: aliceblue;
        text-decoration: none;
        padding: 32px 22px;
    }

    .navbar li a:hover,
    .navbar li a.active {
        color: darkgreen;
        text-decoration: underline;

    }

    /* Right box for buttons  */
    .right {
        /* border: 2px solid green;
        border-radius: 20px; */
        color: white;
        position: absolute;
        display: block;
        margin: 140 auto;
        right: 0px;
        top: 0px;

    }

    .account {
        display: inline-block;
    }

    .account li {
        display: inline-block;
        color: azure;
    }

    .account li a {
        color: aliceblue;
        text-decoration: none;
        padding: 32px 22px;
        font-family: 'Indie Flower', cursive;
    }

    .account li a:hover,.account li a.account {
        color: darkgrey;
    }
    .account img{
        width: 20px;
    }
    .account img:hover{
         border: 2px solid rgb(235, 231, 232);
        background-color: darkgray;
    }

    .myimage {
        /* border: 3px solid red; */
        border-radius: 20px;
        display: inline-block;
        position: absolute;
        left: 190px;
        top: 590px;

    }

    .myimage img {
        width: 350px;
        border: 6px solid rgb(164, 157, 157);
        border-radius: 30px;
       box-shadow: 10px 10px lightgreen;
    }
/* 
    .intro {
        color: darkgray;
        font-size: 40px;
        border: 2px solid red; 
        border-radius: 40px;
        display: block;
        padding: 1px;
        margin: 155px 553px;
        margin-right: 127px;
        margin-left: 615px;
        text-align: center;
        font-weight: bold;
    } */
    .intro img{
        width: 50px;
    }
    .copy{
        color: whitesmoke;
        text-align: center;
        position: absolute;
        right: 500px;
        top: 1400px;
    }
    .end {
        color: white;
        position: absolute;
        display: block;
        margin: 140 auto;
        right: 600px;
        top: 1335px; 
    }
    .account2 {
        display: inline-block;
    }
    .account2 li {
        display: inline-block;
        color: azure;
    }

    .account2 li a {
        color: aliceblue;
        text-decoration: none;
        padding: 32px 22px;
        font-family: 'Indie Flower', cursive;
    }
    .account2 img{
        width: 20px;
    }
   /* bug informatin */
    .buginfo{
        display: flex;
    justify-content: space-evenly;
    flex-wrap: wrap;
    }
     .bug img{
         width: 160px;
         position:absolute;
         left: 740px;
         bottom: -70px;
     }  
     .bug samp{
         /* border: 2px solid red; */
         font-weight: bold;
         font-size: 20px;
         color:white;
         position: absolute;
         left: 730px;
         bottom: -95px;
         display: block;
         
     }   
      #bug1{
        /* border: 2px solid gold; */
         font-size: 18px;
         text-align: justify;
         font-weight: lighter;
         color:lightgray;
         position: absolute;
         left: 610px;
         bottom: -125px;
     }     
     /* ctf information css    */
     .ctf img{
        width: 160px;
         position:absolute;
         left: 1255px;
         bottom: -70px;
     }  
     .ctf samp{
        /* border: 2px solid red; */
        font-weight: bold;
        font-size: 20px;
        color:white;
        position: absolute;
        left: 1238px;
        bottom: -97px;   
     }
     #ctf1{
         font-size: 18px;
         text-align:inherit;
         font-weight: lighter;
         color:lightgray;
         position: absolute;
         left: 1100px;
         bottom: -170px;
     }
     /* pentest information */
   .pentest img{
         width: 200px;
         position:absolute;
         left: 980px;
         bottom: -430px;
   }  
   .pentest samp{
        /* border: 2px solid red; */
        font-weight: bold;
        font-size: 20px;
        color:white;
        position: absolute;
        left: 970px;
        bottom: -440px;   
     }
     #pen1{
         font-size: 18px;
         text-align:inherit;
         font-weight: lighter;
         color:lightgray;
         position: absolute;
         left: 730px;
         bottom: -470px;
     }
</style>

<body>
    <header class="header">
        <!-- Left box for logo -->
        <div class="left">
            <img src="photo_2022-02-27_12-49-12.jpg" alt="">
            <div>CyberHunter</div>
        </div>

        <!-- Mid box for navbar -->
        <div class="mid">
            <ul class="navbar">
                <li><a href="#" class="active">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="resume.html">Resume</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </div>
        <div class="senter">
            <img src="https://img.icons8.com/color/452/cyber-security.png" alt="">
        </div>

        <!-- Right box for buttons -->
        <div class="right">
            <ul class="account">
                <li><a href="#">
                        <img src="https://img.freepik.com/free-vector/instagram-icon_1057-2227.jpg?t=st=1646456790~exp=1646457390~hmac=522addfd9addb99e36f22fe750ef0dc5b1905f1daffbdc7d869c5e92293b1590&w=740"
                            alt="">
                    </a></li>
                <li><a href="#">
                        <img src="https://raw.githubusercontent.com/peterthehan/peterthehan/7029bb807325ea4ed58ee1fdef16f6f4780c8654/assets/twitter.svg"
                            alt="">
                    </a></li>
                <li><a href="#">
                        <img src="https://raw.githubusercontent.com/peterthehan/peterthehan/7029bb807325ea4ed58ee1fdef16f6f4780c8654/assets/linkedin.svg"
                            alt="">
                    </a></li>
                <li><a href="#">
                        <img src="https://raw.githubusercontent.com/peterthehan/peterthehan/7029bb807325ea4ed58ee1fdef16f6f4780c8654/assets/facebook.svg"
                            alt="">
                    </a></li>
                <li><a href="#">
                        <img src="https://raw.githubusercontent.com/peterthehan/peterthehan/7029bb807325ea4ed58ee1fdef16f6f4780c8654/assets/youtube.svg"
                            alt="">
                    </a></li>
            </ul>
        </div>

        <!-- my image for information -->
        <div class="myimage">
            <img src="photo_2022-03-01_15-47-30.jpg" alt="">
        </div>

        <!-- my intro  -->
        <!-- <div class="intro">Hello World<br>I'm,Rushikesh Thakur<br>
        </div> -->

        <!-- bug image  -->
        <div class="buginfo">
        <div class="bug">
            <img src="https://img.icons8.com/external-kiranshastry-gradient-kiranshastry/344/external-bug-cyber-security-kiranshastry-gradient-kiranshastry-2.png" alt="">
            <samp>
                Bug Bounty Hunter <br>
            </samp>
            <samp id="bug1">
                Doing bug bounty hunting currently ranked
            </samp>
        </div>
            <div class="ctf">
                <img src="https://img.icons8.com/external-kiranshastry-gradient-kiranshastry/344/external-flag-outdoor-kiranshastry-gradient-kiranshastry-1.png" alt="">
                <samp>
                    CTF Player 
                </samp>
                <samp id="ctf1">
                    I actively take part in web based CTF(Capture the flag) challenges to learn new things and sharpen my skills
                </samp>
            </div>
            <div class="pentest">
                <img src="https://img.icons8.com/nolan/344/security.png" alt="">
                <samp >
                    Penetration Testing
                </samp>
                <samp id="pen1">
                    Doing Web application security assessments and network security testings
                </samp>
            </div>
        </div>

            <div class="end">
                <ul class="account2">
                    <li><a href="#">
                            <img src="https://img.freepik.com/free-vector/instagram-icon_1057-2227.jpg?t=st=1646456790~exp=1646457390~hmac=522addfd9addb99e36f22fe750ef0dc5b1905f1daffbdc7d869c5e92293b1590&w=740"
                                alt="">
                        </a></li>
                    <li><a href="#">
                            <img src="https://raw.githubusercontent.com/peterthehan/peterthehan/7029bb807325ea4ed58ee1fdef16f6f4780c8654/assets/twitter.svg"
                                alt="">
                        </a></li>
                    <li><a href="#">
                            <img src="https://raw.githubusercontent.com/peterthehan/peterthehan/7029bb807325ea4ed58ee1fdef16f6f4780c8654/assets/linkedin.svg"
                                alt="">
                        </a></li>
                    <li><a href="#">
                            <img src="https://raw.githubusercontent.com/peterthehan/peterthehan/7029bb807325ea4ed58ee1fdef16f6f4780c8654/assets/facebook.svg"
                                alt="">
                        </a></li>
                    <li><a href="#">
                            <img src="https://raw.githubusercontent.com/peterthehan/peterthehan/7029bb807325ea4ed58ee1fdef16f6f4780c8654/assets/youtube.svg"
                                alt="">
                        </a></li> 
                </ul>
            </div>
            <div class="copy"> Copyright © 2022, All rights reserved.
                Personally Crafted 🎨 Rushikesh Thakur <hr>

            </div>
        </div>
    </header>
</body>

</html>
