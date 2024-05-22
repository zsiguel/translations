<html>
    <meta charset="UTF-8">
<head>

</head>
<style>

    .background{
        position: fixed;
        z-index: -50px;
        width: 100%;
        height: 100%;
        left: 0em;
        top: 0em;
    }

    .banner{
        position: fixed;
        z-index: -40px;
        height: 400px;
        width: 50%;
        left: 50%;
        top: 0%;
        transform: translate(-50%, 0%);
        border-radius: 5%;
    }

    .pipp{
        position: fixed;
        z-index: -40px;
        width: 15%;
        right: 0%;
        top: 2%;
        transform: translate(-50%, 0%);
    }

    .zipp{
        position: fixed;
        z-index: -40px;
        width: 18%;
        left: 12%;
        top: 2%;
        transform: translate(-50%, 0%);
    }

    .welcome{
        font-family: Arial, Helvetica, sans-serif;
        font-weight: bolder;
        z-index: 1px;
        font-size: 70px;
        position: fixed;
        left: 50%;
        top: 0%;
        transform: translate(-50%, -25%);
    }

    .welcome2{
        font-family: Arial, Helvetica, sans-serif;
        font-weight: bolder;
        z-index: 1px;
        font-size: 60px;
        position: fixed;
        text-align: center;
        left: 50%;
        top: 15%;
        transform: translate(-50%, -25%);
    }

    .ENG{
        font-family: Arial, Helvetica, sans-serif;
        font-weight: bolder;
        font-size: 40px;
        position: fixed;
        left: 100%;
        top: 0%;
        transform: translate(-110%, 0%);
    }
    .comics{
        font-family: Arial, Helvetica, sans-serif;
        font-weight: bolder;
        font-size: 40px;
        position: fixed;
        text-align: center;
        left: 50%;
        top: 50%;
        transform: translate(-50%, 0%);
    }

</style>
</html>
<body>
    <img class="background" src="pics/background.jpg" alt="">
    
    <img class="banner" src="pics/large.png" alt="">

    <img class="pipp" src="pics/pipp.png" alt="">

    <img class="zipp" src="pics/zipp.png" alt="">

    <div class="welcome">
        <p >Üdv az oldalamon!</p>
    </div>

    <div class="welcome2">
        <p >Kellemes időtöltést!</p>
    </div>

    <div class="ENG">
        <a  href="eng.html">ENG</a>
    </div>
    <!--egyelőre csak képregények-->
    <div class="comics">
        <a  href="hun/lobby.html">Képregények</a>
    </div>

</body>