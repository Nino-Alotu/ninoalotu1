<html>
<head>
    <title>My_profil</title>
    <style>
      body{
    margin: 0;
    padding: 0;
    background-color:black;
}
nav{
    display: flex;
    border-bottom: 1px solid rgb(255, 255, 255);
    box-shadow: 0 0 2rem blue;
    align-items: center;
    justify-content: space-around;
    position: fixed;
    width: 100%;
}

nav ul{
    display: flex;
    list-style: none;
}
.logo1{
    color: rgb(228, 141, 219);
}
.logo1 span{
    color: rgb(240, 207, 22);
}
nav ul li a{
    text-decoration: none;
    color: white;
    padding: 0 20px;

}
nav ul li a:hover{
    color: red;
}
.cari{
    background-color: blueviolet;
    height: 40px;
    width: 260px;
    align-items: center;
    display: flex;
    border-radius: 50px;
}
.cari input{
margin-left: 15px;
border: none;
height: 25;
font-size: 1rem;
background:none;
color:white;
border-bottom: 1px solid white;
border-left: 1px solid white;
}
.cari img{
    height: 25px;
    width: 25px;
    margin-left: 5px;
    cursor: pointer;
}


/* hero */
.hero{
    color: white;
    display: flex;
    justify-content: space-around;
    margin-left:70px;
    margin-right: 70px;
    align-items: center;
    height: 100vh;
}
.hero img{
    height: 300px;
    width: 300px;
    border-radius: 300px;
    box-shadow: 0 0 1rem blue;
   
    
}

/* footer */
.footer1{
    border-top: 1px solid rgb(255, 255, 255);
    box-shadow: 0 0 2rem blueviolet;
    z-index: 999;
    bottom: 0;
    position: fixed;
    width: 100%;
    text-align: center;
}
.footer1 p{
    color: white;
    font-weight: bold;
}


@media screen and (max-width:720px){
    nav ul{
    display: none;
    }
    .hero{
        flex-wrap: wrap;
        height: 140vh;
    }
    .cari{
        height: 25px;
        width: 170px;
    }
    .cari input{
        height: 15px;
        font-size: 10px;
    }
    .cari img{
        height: 15px;
    width: 15px;
    }
}
    </style>
</head>
<body>
    <nav>
        <h2 class="logo1">MY <span>PROFIL</span></h2>
        <ul>
            <li><a href="">Home</a></li>
            <li><a href="">About</a></li>
            <li><a href="">Locasi</a></li>
            <li><a href="">Contac</a></li>
        </ul>
        <div class="cari">
            <input type="text" placeholder="Atu buka c1">
            <a href="#/kopi/index.html"><img src="111.png" alt=""></a>
        </div>
    </nav>
    <!-- hero -->
    <div class="hero">
        <img src="195559773.jpg" alt="">
        <h4><span>MY_PROTOFOLIO</span>
        
        </h4>
    </div>
    <!-- hero end -->

    <!-- footer -->
     <footer>
        <div class="footer1">
            <p>Developmen by Nino_Alotu 🤦😍😏👎<br>
                <a href="#tiktok.com">tiktok.com</a>
                <a href="www.youtube.com/@angelinosarmento8933">youtube.com</a>
            </p>
        </div>
     </footer>
</body>
</html>
