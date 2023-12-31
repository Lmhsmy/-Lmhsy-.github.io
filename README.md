# -Lmhsy-.github.io
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=, initial-scale=1.0">
    <title>RECODES</title>
    <link rel="stylesheet" href="style.css"
</head>
<style>* {
    padding: 0;
    margin: 0;
}
header{
    background-color: black;
    height: 80px;
    width: 100%;
    position: relative;  
}
h1{
    color:white ;
    position: relative;
    left: 120px;
    top: 0;
    line-height: 80px;
}
header ul{
    position: absolute;
    right: 5vw;
    top: 0;
    line-height: 80px;
}
header li{
    display: inline;
    margin-right: 5vw;
}
header a{
    color: white;
    text-decoration: none;
}
header a:hover{
    text-decoration: underline;
}



    * {
        padding: 0;
        margin: 0;
    }
    .shell{
        height: 100vh;
        overflow-x: hidden;
        perspective: 3px;
    }
    .shell div{
        position: relative;
        display: flex;
        justify-content: center;
        align-items: center;
        font-style: 30px;
        letter-spacing: 2px;
    }
    .image{
        transform: translateZ(-1px) scale(1.6);
        background-size: cover;
        height: 100vh;
        z-index: -1;
    }
    .text{
        height: 50vh;
        background-color: #fff;
    }
    .text h1{
        color: #000;
    }
    .heading{
        z-index: -1;
        transform: translateY(-30vh) translateZ(1px);
        color: #fff;
        font-size: 30px;
    }
    .menu{
        display: none;
    }

    @media screen and ( max-width: 768){
        .menu{
            display: block;
            background-color: transparent;
            color: white;
            font-size: 35px;
            position: absolute;
            top: 15px;
            left: 20px;
            border: none;
            cursor: pointer;
            }
        }
    </style>

<body>
    <header>
    <button class="menu">&#9776;</button>
    <h1>RECODES</h1>
    <nav>
    <ul>
        <li><a href="#bbb5ac">About us</a></li>
        <li><a href="#bbb5ac">Game</a></li>
        <li><a href="#bbb5ac">Library us</a></li>
    </ul>
    </nav>
</header>



    <div class="shell">
        <div class="image" style="background-image: url('./img/1.png');"></div>
        <div class="heading">
            <h1>Here's the archive</h1>
        </div>
        
        <div class="">
        <video width="3000" height="1820" controls>
            <source src="video/Voyeur -Game Trailer.mp4" type="video/mp4">
            </video>
        </div>

        <div class="text">
            <h1>Hong Kong in the 1980s</h1>
        </div>
        <div class="image" style="background-image: url('./img/6.png');"></div>
        <div class="heading">
            <h1>Constructing the Self from Constructing the Other in the Dispute </h1>
        </div>

        <div class="heading"><h1>between Globalisation and Localisation</h1>
        </div>
        <div class="text">
            <h1>People exploring themselves in the confusion of 1997</h1>
        </div>


        <div class="image" style="background-image: url('./img/4.png');"></div>
        <div class="heading">
            <h1>When prople leave you</h1>
        </div>
        <div class="text">
            <h1>People leave to work, like dandelions.</h1>
        </div>

        
        <div class="image" style="background-image: url('./img/5.png');"></div>
        <div class="heading">
            <h1>Seeking a door in the concrete jungle.</h1>
        </div>

    </div>
<footer>
    <p>Please contact us if you want to cooperate</p>
</footer>
</body>

</html>
