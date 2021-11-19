<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Frozeneats.com</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Great+Vibes&display=swap" rel="stylesheet">




    <style>
     :root{
         color: 1px #ffc4eb;
         color: 2px #f3eac4;
         color: 3px #fdfefd;
         color: 4px #0d1010;
         color: 5px #abc798;




     }
        .logo
        {
            display:flex;
            justify-content: center;
            font-size: 20px;
            background-color:#abc798;
        }
        .logo img{
            height:80px;
            width:100px;
        }
        .logo h1{
            font-family: 'Great Vibes', cursive;
        }
        marquee
        {
            font-family: 'Great Vibes', cursive;
            font-size: 30px;
        }
        .navbar
        {   display:flex; 
            
            background-color: #ffc4eb;
            justify-content:space-evenly;
            align-items: center;
             text-align: center;   
            height:50px;
            width:100%;
        }
        .navbar li{

            list-style: none;
            margin: 4px;
        }
        .navbar li a{
            text-decoration: none;
            font-size: 25px;
        }
        .navbar li a:hover
        {
            background-color: #abc798;
            border-radius: 10px;
        }
      /*  .gallery
        {
            display: flex;
            
            height:200px;
            width: 200px;
            transition:width 2s ease-in-out ;
        }
        .gallery img:hover
        {   
            height: 100px; 
            width: 150px;
            transform: scale(3);
        }*/
        .home{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background: url("images/icecreambackgrd.jpg") no-repeat center center/cover;
    width: 100%;
    height: 50vh;
}
.home h2{
    opacity: 1;
}
.home p{
 font-size: 20px;
}
.home::after{
    content: "";
    position: absolute;
    /* z-index: -1; */
    /* z-index: '-1'; */
    opacity: 0.5;
}

/* services */
.services{
    display: flex;
    height: 200px;
    width: 100%;
    justify-content: center;
    align-items: center;
    background-color: #abc798;
    border-radius: 80px;
    margin: 10px;
}
.items{
    height: 100px;
    width: 300px;
    margin: 5px;
    padding: 5px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    
    
}
.items h2{
    font-family: 'Great Vibes', cursive;
    font-size: 30px;
}
#items1{
    border-right: 2px solid #f3eac4;
}
#items2{
    border-right: 2px solid #f3eac4;
}

/* Gallery */
h1{
    font-family: 'Great Vibes', cursive;
    text-align: center;    
}
.gallery{
    display: flex;
    justify-content: space-evenly;
    flex-wrap: wrap;
}
.gallery img{
    border-radius: 4px;
    transition: all 2s ease-in-out;
    height: 200px;
    width:200px;
    object-fit: cover;
    padding: 20px 20px 20px 20px;
    flex-grow: 1;
    flex-basis: 0;
    transition: .5s;

}
.gallery img:hover{
    border-radius: 20px;
    transform: scale(2);
  /*  flex-basis: 30%;*/
}

/* Contactus */
.contact{
    background-color: #ffc4eb;
    display: flex;
    flex-direction: column;
    justify-content: center;
    /* align-items: center; */
}
.detail{
    width: 50%;
    margin: 5px;
}
#message{
    height: 50px;
}




    </style>
</head>
<body>
    <header>
        <div class="logo">
            <img src="images/logo.png">
            <h1>Frozen Treats</h1>



        </div>
        <hr>
        <marquee>Ice cream solves everything</marquee>
        <hr>




    </header>

    <ul class="navbar">
        <li><a href="#">Home</a></li>
        <li><a href="#">Our Services</a></li>
       <li><a href="#">About Us</a></li>
        <li><a href="#">Contact Us</a></li>

        



    </ul>
    <section class="home">
        <h2>Welcome to Sweet World</h2>
        <p>

            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quidem, aperiam.</p>
        
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ullam, magni.</p>
        <button id='button'>
            Order Now
        </button>
    </section>

    <section class="services">
        <div class="items" id="items1">
            <h2>Waffle</h2>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Asperiores suscipit deleniti eveniet dicta ab, possimus iure cum culpa ratione velit praesentium sed.</p>
        </div>
        <div class="items" id="items2">
            <h2>Ice Cream</h2>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Accusamus, quia eaque! Perspiciatis sint amet cumque commodi eveniet ab, debitis impedit nostrum obcaecati?</p>
        </div>
        <div class="items" id="items3">
            <h2>Shakes</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tempore, tempora, dolores consequuntur quisquam repellat velit reprehenderit, amet aut culpa corrupti dolorem ullam.</p>
        </div>
    </section>
    <h1>

    <div class="gallery">
        <img src="images/download.jpg" class="ice1">
        <img src="images/images.jpg">
        <img src="images/istockphoto-1249206105-170667a.jpg">
        <img src="images/istockphoto-1289144766-170667a.jpg">
        <img src="images/photo-1560008581-09826d1de69e.jpg">
        <img src="images/photo-1630936653848-61d14b90cf86.jpg">






    </div>

    <h1>Contact Us</h1>
    <form action="" class="contact">
        Name:<input type="text"  class="detail" placeholder="Name">
        E-mail ID:<input type="email" class="detail" placeholder="Email-id">
        Phone no.:<input type="number" class="detail" placeholder="Phone no">
        Message:<input type="text" class="detail" id="message" placeholder="Message">
    </form>

</body>
</html>
