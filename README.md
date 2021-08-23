# Animated-Website3
<!DOCTYPE html>
<html>
    <head>
        <title></title>
        <link rel="stylesheet" type="text/css" href="css/style.css">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/3.7.2/animate.min.css">
    </head>

    <body>
        <header>
            <nav>
                <div class="logo"> <h1 class="animated infinite heartBeat ">Mera bharath</h1></div>
                <div class="menu">
                    <a href="#">Home</a>
                    <a href="gal.htm">Gallery</a>
                    <a href="https://www.incredibleindia.org/content/incredible-india-v2/en.html">About</a>
                    <a href="cont.htm">Contact</a>
                </div>
            </nav>

                <main>
                    <section>
                        <h3>Welcome To India</h3>
                        <h1>DO COME & VISIT<span class="change_content"></span></h1>
                        <p>"India once is not enough"</p>
                        <a href="https://en.wikipedia.org/wiki/Tourism_in_India" class="btnone">learn more</a>
                        
                    </section>
                </main>
        </header>

    </body>
</html>

<html>
    <head>
        <title>GALLERY</title>
    </head>

    <body >
        <img width="1200" height="600" src="https://s3.india.com/travel/wp-content/uploads/2015/08/yar.jpg" alt="LOGO"/>
        <p>
            Yatra too has associations with credit cards and there is a lot you can save up if you enjoy planning and booking your travel packages with yatra. In all honesty, the benefits are more specifically for frequent users of the service.
        </p>

        <a href=" http://www.yatra.com">Click Here to contact Us</a>
        <br>
        <br><br>

        <a href="index4.htm">Click here to go home page</a>
    </body>
</html>

<html>
    <head>
        <title>GALLERY</title>
    </head>

    <body >
        <img width="1500" height="1000" src="C:\Users\I Love Mom & Dad\Desktop\Animated Website\images\gal.jpg" alt="GALLERY"/>
        <a href="index4.htm">Click here to go home page</a>
    </body>
</html>

*{
    margin: 0; padding: 0;box-sizing: border-box;
}

header{
    width: 100%; height: 100vh;
    background-image:linear-gradient(rgba(0, 0, 0, 0),rgba(0, 0, 0, 0.007)), url('../images/taj.jpg');
    background-repeat: no-repeat;
    background-size: cover;
}
nav{
    width: 100%;height: 15vh;
    background: rgba(0,0,0,0.2);
    color: white;display: flex;justify-content: space-between;
    align-items: center;text-transform: uppercase;
}
nav .logo{
    width: 25%;text-align: center;
}

nav .menu{
    width: 40%; 
    display: flex;justify-content: space-between;
}
nav .menu a{
    width: 25%;
    text-decoration: none;color: white;
    font-weight: bold;
}

nav .menu a:first-child{
    color: #14dfb6;
}

main{
    width: 100%;
    height: 85vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;
}


section h3{
    font-size: 35px;
    font-weight: 200;
    letter-spacing: 3px;
    text-shadow: 1px 1px 2px black;
}
section h1{
    margin: 30px 0 20px 0;
    font-size: 55px;
    font-weight: 700;
    text-shadow: 2px 1px 5px black;
    text-transform: uppercase;
}
section p{
    font-size: 25px;
    color:  #eee;
    word-spacing: 2px;
    margin-bottom: 25px;
    text-shadow: 1px 1px 1px black;
}
section a{
    padding: 12px 30px;
    border-radius: 4px;
    outline: none;
    text-transform: uppercase;
    font-size: 13px;
    font-weight: 500;
    text-decoration: none;
    letter-spacing: 1px;
    transition: all .5s ease;
}


section .btnone{
    background: #00b894;
    color: white;
}

.btnone:hover{
    background: white;
    color: black;
}
.change_content:after{
    content: ' ';
    animation: changetext 10s infinite linear;
    color: #8efde7;

}

@keyframes changetext{
    0%{content: " darjeeling";}
    20%{content: " agra";}
    35%{content: " jaipur";}
    60%{content: " kerala";}
    80%{content: " delhi";}
    100%{content: " mumbai";}
}
