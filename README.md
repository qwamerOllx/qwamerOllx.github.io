<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css" integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
        <title>My version of Ghana Communication Technology University (GCTU) webpage</title>
        
    </head>
    <style>
        body {
            background-image: url("rp3.jpg");
            background-repeat: no-repeat;
            background-size: cover;
            background-position: center;
            width: 100%;
            justify-content:center;
            display: inline;
            margin: 0;
            max-width: 100%;
            align-items: normal;
            align-content: normal;
            padding: 0;
            background-color:teal;
            line-height: 1.5em;
            border-radius: 5px;
        }
        .welcome {
            font-family:system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
            width: 100%;
            color: rgb(10, 1, 1);
            justify-content:center;
            align-items: center;
            border-radius: 5px;
            padding: 0;
            margin-left: 0;
            text-align: center;
            /*background-image: url(mawuli.png);*/
            opacity: 100%;
            
        }

        .main {
            background-color: aliceblue;
            border-radius: 20px;
            padding: 0;
            border-width: 100%;
            display: inherit;
            align-content: space-around;
            max-width: 80%;
            min-width: none;
            margin-left: 8em;
            height: 80%;
            opacity: 100%;
            padding-bottom: 5em;
            padding-top: 5em;
            box-shadow: 5px 5px #1c1c1c00;
        }
        .logo {
            font-family:berlin sans fb ;
            display: inline;
            align-items:unset;
            justify-content:left;
            margin-left:0;
            margin-right: 0;
        }
        .SIP {
            width: 100%;
            justify-content: center;
            font-family: candara;
            font-weight: bold;
        }
        .form {
            justify-items: center;
            display: inline-flex;
            flex-wrap: wrap;
            gap: 1em;
        }
        .user {
            flex: 1 0 8rem;
            border-radius: 5px;
            height: 2em;
            background-color: snow;
        }
        .pass {
            flex: 1 0 8rem;
            border-radius: 5px;
            height: 2em;
            background-color: snow;
        }
        button {
            flex: 1 0 4rem;
            background-color: darkblue;
            color: ghostwhite;
            border-radius: 7px;
            height: 2em;
            border: thin;
        }
        p {
            text-align: center;
            font-size: medium;
            color: red;
        }
        .col-lg-6{
            text-align: center;
        }
        .social-net {
            margin: 0;
           display: inline;
           
        }
        /*
        h1 {
        animation: linear 2s ease-in alternate forwards;
        transform: translateY(-20px);
        }
        */
        .hr-or {
            display: inline-flex;
            width: 45%;
            margin: 0;
        }
        .footer {
            position:relative;
            width:100%;
            bottom: 0;
            margin: 0;
            left: 0;
            padding: 7px 8px;
            text-align: center;
            font-family: monospace;
            background-color:black;
        }
        .footer a{
            display: inline-flex;
	        text-align:center;
	        background-color: transparent;
            text-decoration: none;
            font-size:18px;
            color: rgb(128, 122, 122);  
        }
        .footer a:hover {
            color: rgb(202, 202, 202);
            font-weight:bolder;
            
        }
        .emoji-o {
            color: rgb(255, 0, 0);
            display: inline;
        }
        .crest:hover {
            filter: drop-shadow(1px 1px 20px yellow);
        }
        #header {
            margin: 0;
            width:auto;
            height: 60px;
            background-color: black;
            font-family:system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;               
        }
        .lens {
        float: right;
        background-color: transparent;
        padding: 7px;
    
        }
        ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            background-color: #000;
            font-weight: bold;
            font-size: x-large;
        }
        li {
            float: left;
            border-right: 1px solid #bbb;
            padding-top: 0;
            border-radius: 5px;
            color:rgb(60, 201, 211)
    
        }
        /*li:last-child {
            border-right: none;            
        }*/
        li a {
            display: block;
            color: white;
            text-align: center;
            padding: 16px 16px;
            text-decoration: none;
            border-radius: 5px;
        }
        li a:hover:not(.active) {
            background-color: #808080;
        }
        .active {
            background-color: #0099ff;
        }
        .bg1 {
            background-color: rgb(255, 221, 0);
            border-radius: 10px;
            margin-left: 35em;
            margin-right: 35em;
        }
    </style>
    <body onload="alert('Hello, Welcome to GCTU SIP page created by Ebenezer from the Computer Science Department.')">
        <div class="container-fluid">
        <div id="header">
            <ul style="display: inline;">
               <li class="active"><a href="#">Home</a></li>
                <li><a href="#">Update</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
                <li><a href="#">News</a></li>
            </ul>
            <!--<img src="lens1.png" style="border-radius: 50%;" width="40" height="40"  class="lens">-->
            <form class="d-flex" role="search" style=" float: right; padding: 0.8em;">
                <input class="form-control me-1" type="search" placeholder="Search" aria-label="Search" style="width: 70%;">
                <button class="btn btn-outline-white" type="submit" style="background-color: #000;"><span class="fa fa-search"></span></button>
            </form>
        </div>
       
        <div class="welcome" >
        <br>
            <h2 style=" font-weight: bolder; font-size: xx-large; color: black;"><strong>꧁༺ա ɛ ʟ ƈ <div class="emoji-o">🅾</div> ʍ ɛ༻꧂</strong></h2>
            
            <br>
            <div class="main">
                <div class="col-lg-6">
                    <div class="logo">
                        <img class="crest" src="gctu.jpeg" width="400" height="400" style="border-radius: 50%; float: left; padding-left: 2em;">
                        <h1 style="display: inline;">GHANA COMMUNICATION <br>TECHNOLOGY UNIVERSITY <br>
                        <h3 style="display: inline; font-family: monotype corsiva; font-size: larger; color: orange;">...Head Heart Hand</h3></h1>
                    </div>
                </div>  

                <div class="SIP">
                    <h2>Student Information Portal <br>(SIP) <br><br> Sign In</h2>
            
                    <form class="form" action="https://site.gctu.edu.gh" method="get">
                        <input type="text" placeholder="Student ID" class="user" required >
                        <input type="password" placeholder="Password" class="pass" required>
            
                        <button>SIGN IN</button>
                
                    </form>
                    <br><br>
                    <span class="">
                    <hr style="width: 19%; display: inline-flex; margin-right: 5px;">or<hr style="width: 19%; display: inline-flex; padding-bottom: 0%; margin-left: 5px;">
                   </span>
                    <p>Forgot your password? <a href="resetPassword.html" target="" style="text-decoration: none; font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;">Click here </a>to do a password reset.</p>
                </div>
            </div><br>
            <div class=" col-lg-6 " style="background-color: goldenrod;">...GCTU</div>
            <div class=" col-lg-6 " style="background-color: rgb(0, 55, 255);">Knowledge comes from learning</div>
            
            
            <footer class="footer">
                <a href="www.eben.com">  Home  </a>
                <a href="www.eben.com">  Learning platform   </a>
                <a href="www.eben.com">  Library  </a>
                <a href="www.eben.com">  News </a>
                <br><br>
                <div class="col-lg-6 bg1" >Follow Us</div>
                
                <br>
                <div class="social-net">
                <a href="https://web.facebook.com/gctu"><img src="transfb.png" alt="facebook" width="40" height="40" style="border-radius: 50%; margin: 5px; background-color: hwb(241 0% 0%);"></a>
                <a href="https://twitter.com/gctu"><img src="transX.png" alt="twitter" width="40" height="40" style="border-radius: 50%; margin: 5px; background-color: rgb(2, 231, 248);;"></a>
                <a href="https://www.instagram.com/gctu"><img src="transIG2.png" alt="Instagram" width="40" height="40" style="border-radius: 50%; margin: 5px; background-color: rgb(255, 0, 0);"></a>
                <a href="www.eben.com"><img src="transSup.png" alt="WhatsApp" width="40" height="40" style="border-radius: 50%; margin: 5px; background-color: rgb(0, 231, 0);"></a>
                <a href="https://www.tiktok.com/@mawulischool"><img src="tiktok.png" alt="Snapchat" width="40" height="40" style="border-radius: 50%; margin: 5px; background-color: rgb(1, 1, 1);"></a>
                <!--<a href="www.eben.com"><img src="tiktok.png" alt="Tiktok" width="30" height="30" style="border-radius: 50%;"></a> -->
                </div>
                <br>
                <a>Copyright © 2024 Ebenezer Adumuah™   </a>
                <br>
                <a href="www.eben.com">  Home |   </a>
                <a href="www.eben.com">  About Us |   </a> 
                <a href="www.eben.com">  Privacy Policy |   </a>
                <a href="www.eben.com">  Help </a>
                <br>
                
                <a>All Rights Reserved.</a>
                 <br><br>
            </footer> 
         
        </div> 
    </body>
</html>
