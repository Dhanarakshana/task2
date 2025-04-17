# task2
<!DOCTYPE html>
<html lang="en">
   <head>
       <meta charset="UTF-8">
       <meta http-equiv="X-CA-compatible" content="IE-edge">
       <meta name="viewport" content="width=device-width" initial-scale="1.0">
       
       <title>Responsive cake website</title>
       <link rel="stylesheet" type="text/css" href="css/style.css">

<style type="text/css">
       *{
        text-decoration:none;
       }
       .navbar{
        background: crimson; font-family: calibri; padding-right: 15px; padding-left: 15px;
       }
       .navdiv{
        display: flex; align-items: center; justify-content: space-between;
       }
       li{
        list-style: none; display: inline-block;
       }
       li a{
        color:green; font-size: 20px; font-weight: bold; margin: 65px;
       }
       button{
        background-color: red; margin-left: 10px; border-radius: 10px; padding: 10px; width: 90px;
       }
       button a{
        color: white; font-weight: bold; font-size: 15px;
       }
       
       /*change the color of the links on hover*/
       .topnav a:hover{
        background-color: #ddd;
        color: red;
    }
    .my_cover{
        width: 100%;
        height: 550px;
        object-fit: cover;
    }

    .container{
        width: 100%;
        height: 550px;
        position: relative;
    }
    
    *{
        margin: 0px;
        padding: 5px;
        box-sizing: border-box;
        font-family: sans-serif;
    }
    body{
        background-color:rgb(250, 249, 248);
    }
    .card-container{
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
        margin-top: 50px;
    }
    .card{
        inline-size: 20px;
        width: 200px;
        margin: 10px;
        background-color: rgba(245, 222, 179, 0.685);
        border-radius: 20px;
        overflow: hidden;
        box-shadow: 0px 2px 4px rgba(0,0,0,0.2);
    }
    .card img{
        width: 100%;
        height: auto;
        border-radius: 4px;
    }
    .card.content h3{
        font-size: 28px;
        margin-bottom: 8px;
    }
    .card.content p{
        font-size: 15px;
        line-height: 1.3;
    }
    .card.content .button{
        border: #666;
        display: inline-block;
        padding: 8px 16px;
        background-color: #333;
        text-decoration:none;
        border-radius: 4px;
        margin-top: 16px;
        color: #b1afaf;
    }
   
    *{
        box-sizing: border-box;
    }
   .column{
         float: left;
         width: 33.33%;
         padding: 5px;
   }
  .row::after{
       content:"";
       display: table;
       clear: both;
  }
    </style>
       <!--navbar-->
       <div class="topnav" id="mytopnav">
        <ul>
            <li><a href="active" style="color: rgb(20, 133, 69);">Cake Bake</a></li>
        <li><a href="active">Home</a></li>
        <li><a href="#service">Service</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
        <button><a href="#buy">Buy</a></button>
    </ul>
  </div> <br>
   </head>
  
   <body>
    <div class="container">
        <img class="my_cover" src="cake cover.png"  >
    </div>
<div class="card-container">
    <div class="card">
        <img src="canvacake1.png">
        <div class="card-content">
            <h3>Card 1</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. </p>
        <a href="" class="button">Read More</a>
    </div>
    </div>

    <div class="card">
        <img src="canvacake2.png">
        <div class="card-content">
            <h3>Card 2</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. </p>
        <a href="" class="button">Read More</a>
    </div>
    </div>

    <div class="card">
        <img src="canvacake3.png">
        <div class="card-content">
            <h3>Card 3</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. </p>
        <a href="" class="button">Read More</a>
    </div>
    </div>

    <div class="card">
        <img src="newcake.png">
        <div class="card-content">
            <h3>Card 4</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit.</p>
        <a href="" class="button">Read More</a>
    </div>
    </div>

    <div class="card">
        <img src="newcake2.png">
        <div class="card-content">
            <h3>Card 5</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit.</p>
        <a href="" class="button">Read More</a>
    </div>
    </div>
    
    <div class="card">
        <img src="newcake3.png">
        <div class="card-content">
            <h3>Card 6</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit.</p>
        <a href="" class="button">Read More</a>
    </div>
    </div>
</div>
<br>
     <h1 style="color: red; text-align: center; background-color: gainsboro;">TODAY'S OFFER</h1>
     <br>
     <img src="cookie.png" height="200px" width="185px">
     <img src="cuppie.png"height="200px" width="185px">
     <img src="croissant.png"height="200px" width="185px">
     <img src="sponch cake slice.png"height="200px" width="185px">
     <img src="brownie.png"height="200px" width="185px">
     <img src="cheesecake.png"height="200px" width="185px">
     <img src="fruitcake.png"height="200px" width="185px">
     <br>
     <h2 style="font-size: larger; color: #8f6666; text-align: center; ">We are exicted to bake for you Today! and Everyday</h2>
     <h1 style="color: #6d4a4a; font-size: bold; text-align: center;">Delicious and Tasty Cakes</h1>
     <h3 style="color: #573b3b; font-size: small; text-align: center;">A Party without cake is really just a meeting</h3>
     <h1 style="color:#472e2e; font-size: smaller; text-align: center;">The taste of Home-Baked goodness to enrich every moment. </h1>
     <br>
  <div class="row">
<div class="column">
  <img class="leftside" src="leftside image.png" width="100%">
</div>
<div class="row">
    <div class="column">
      <img class="leftside" src="wedding cake.png" width="100%">
    </div>
    <div class="row">
        <div class="column">
          <img class="leftside" src="cupcakes grp.png" width="100%">
        </div>   
</div> 
 
   </body>
   <h1 style="color: green; text-align: center;">CAKE BAKE</h1>
   <h2 style="color: green; text-align: center;">12/32, ABC Road, Mumbai, India</h2>
   <h2 style="color: green; text-align: center;">Email: cakebakeindia@gmail.com</h2>
   <h2 style="color: green; text-align: center;">+91 1234567891</h2>
   <h2 style="color: green; text-align: center;">Insta:Cake Bake India</h2>
   <h2 style="color: green; text-align: center;">Whatsapp:+91 0987654321</h2>
   <script src="main.js"></script>
</html>
