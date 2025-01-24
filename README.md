<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>saloni</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css" integrity="sha512-Kc323vGBEqzTmouAECnVceyQqyqdsSiqLQISBL29aUW4U/M7pSPA/gEUZQqv1cwx4OnYxTxve5UMg5GT6L4JJg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <style>
        
        .profile-container{
            display: flex;
            flex-direction: column;
            height: 400px;
            width: 400px;
            border: 1px solid black;
            align-items: center;
            margin: auto;
            margin-top: 50px;
            background-color: rgba(0, 0, 0,0.5);
        }
      img{
        
        height: 97px;
        width: 140px;
        position: absolute;
        left: 380px;
        top:70px;
        border-radius: 50%;
      }  
      h2{
        position:absolute;
        top: 170px;
        left: 350px;
      }
        .btn{
            position: absolute;
            top:270px;
            left: 410px;
            background-color: black;
            color: white;
            border-radius: 10px;
            border-style: none;
        }
        .btn:hover{
            background-color:rgb(122, 8, 110);
            transform: scale(1.1);
        }
        ul{
            position:absolute;
            top: 300px;
            left: 300px;
            display:inline-flex;
            list-style-type: none;
            letter-spacing:50px;
            font-size:25px;

        }
        
        .social{
            color:black;
            position: absolute;
            top: 400px;
            left: 340px;
            word-spacing: 40px;
        }
        .fa-solid:hover{
            color: rgb(16, 70, 171);
            transform: scale(1.1);

        }
        .fa-brands:hover{
            transform: scale(1.2);
        }
        p{
            position: absolute;
            top:215px;
            left:360px;
            font-weight: bold;
            color:rgb(11, 96, 28);
            
        }
    </style>
</head>
<body>
   <div class="profile-container">
    <div class="image">
        <img src="saloni.png.jpg">
    </div>
    <div class="name">
    <h2 title="SALONI">Miss Saloni<span> Tanwar</span></h2>
    <p>WEBSITE DEVELOPER</p>
</div> 
<button class="btn" onclick="follow()">
    Follow
    <i class="fa-solid fa-user-plus"></i>
</button>
<ul>
    <li>
        <a class="fb" href="#" style="color:darkblue;">
            <i class="fa-brands fa-facebook"></i>
        </a>
    </li>
    <li>
        <a class="yt" href="#" style="color: darkred;">
            <i class="fa-brands fa-youtube"></i>
        </a>
    </li>
    <li>
        <a class="tw" href="#" style="color:rgb(29,161,242);">
            <i class="fa-brands fa-twitter"></i>
        </a>
    </li>
    <li>
        <a class="insta" href="#" style="color:purple;">
            <i class="fa-brands fa-instagram"></i>

        </a>
    </li>
</ul>
<div class="social">
    <i class="fa-solid fa-heart">20L</i>
    <i class="fa-solid fa-comment">15k</i>
    <i class="fa-solid fa-share">100k</i>
</div>
   </div>
   </body>
   
</html>
