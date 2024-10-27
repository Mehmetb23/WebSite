# Welcome to GitHub Desktop!

This is your README. READMEs are where you can communicate what your project is and how to use it.

Write your name on line 6, save it, and then head back to GitHub Desktop.
<!DOCTYPE html>
<html lang="en">
<head>
    <title>SEDAT TAMİR</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="Untitled-1.css">
</head>
<body>
    <div class="container">
    <div class="navbar">
<div class="logo"> 
<a href="^#">Sedat Sihhi Tesisat
</a>

</div>
<ul>
<li><a href="#" class="active">Ana Sayfa</a></li>
<li><a href="#">Hakkımızda</a></li>
<li><a href="#">Hizmetler</a></li>
<li><a href="#">Ürünler</a></li>
<li><a href="#">İletişim</a></li>
</ul>
 </div>
<div class="center">
<h1>Sedat Sihhi Tesisat</h1>
<h2>Hoşgeldiniz</h2>
 
 </div>
</div>
    
</body>
</html>

@import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300..800;1,300..800&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap'); 
*{
    margin: 0;
    padding: 0;
    }
 
    .container{
     background: url(bg.jpeg);
     height: 100vh;
     background-size: 100% 100%;
      } 

      .container .navbar{
      width: 100%;;
      height: 70px;
      background: rgba(26, 102, 190, 0.4)
    }

.navbar .logo{
    display: inline-block;
    margin-left: 50px;
    margin-top: 20px;
}

.navbar .logo a{
 text-decoration:none;
 font-size:30px;
font-family:sans-serif;
color:#f3f3f3
} 


.navbar ul{
    float: right;
    margin-right: 20px;
}   

.navbar ul li{
list-style:none;
display:inline-block;
margin:0 8px;
line-height:80px;
}

.navbar ul li a{
    color: white;
    text-decoration:none;
    font-size:20px;
    padding:6px 13px;
    font-family:system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}

.navbar ul li a.active,
.navbar ul li a:hover{
background:#a4bce9;
border-radius: 2px;

}

.container .center{
    position:absolute;
    top:50%;
    left:50%;
    transform: translate(-50%,-50%);
    font-family:sans-serif;
    user-select: none;

}

.center h1{
    color: #544888;
    font-size: 70px;
    font-weight: bold;
    width: 900px; 
    text-align: center;
}



.center h2{
    color: #0e0e0e;
        font-size:50px;
    font-weight: bold;
width:885px;
margin-top: 10px;
text-align: center  ;
}
