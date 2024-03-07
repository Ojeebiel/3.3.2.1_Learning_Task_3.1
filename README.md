<html>
    
    <head>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Madimi+One&family=Montserrat:ital,wght@1,600&display=swap" rel="stylesheet">

        <title>Test</title>
        <style>

            b{
                font-family: "Madimi One", sans-serif;
                font-weight: 400;
                font-style: normal;
                color: white;
            }
            #title{
                background-color: rgb(58, 97, 51);
                z-index: -1;
                border-radius: 10px;
                background-image: linear-gradient(to right, rgb(58, 97, 51), rgb(192, 205, 51));
                padding: 10px; }

            .font{
                font-size: 54px;
            }
            .centerPic {
                padding-top: 35px;
                display: block;
                margin-left: auto;
                margin-right: auto;
                width: 50%;

            }
            .center {
                margin: auto;
                width: 55%;
                padding-top: 10px;
            }
            .centerInsideText {
                margin: auto;
                width: 75%;
                padding-top: 20px;
                text-align: center;
                color: white;
                font-family: "Madimi One", sans-serif;

            }
            #wrapper{
                width: 1490px;
                height: 900px;
                padding: 2px;
                border: 0px solid black;
            }
            #wrapper div{
                width: 252px;
                height: 400px;
                margin: 21px;
                border: 2px solid white;
                float: left;
                font-size: 24px;
                background: transparent;
                backdrop-filter: blur(8px);     
                border-radius: 10px;            
            }
            #myVideo {
                right: 0;
                bottom: 0;
                width: 100vw;
                height: 100vh;
                margin: auto;
                position: fixed;
                height: auto;
                
            }
            .content {
                position: fixed;
                bottom: 80;
                width: 100%;
                padding: 20px;
            }

        </style>

        <body>
            
            <video autoplay muted loop id = "myVideo">
                <source src="marketPlace.mp4" type="video/mp4">
                Your browser does not support HTML5 video.
              </video>

            <div class = "content">
                <div class = "center">
                    <p class = "font">
                        <b id = "title">
                            MY Top 10 Favorite Foods
    
                        </b>
                      
                    </p>
                    <div id = "wrapper">

                        <a href = "https://en.wikipedia.org/wiki/Fried_chicken"  target="_blank">
                            <div>
                                <br>
                                <img src="fried_chicken.jpeg" height = 100px width = 100px class = "centerPic">
                                <p class = "centerInsideText">
                                    FRIED<br>CHICKEN
                                    <br><br>
                                    Dish of chicken cooked until brown                        
                                </p>
                            </div>
                        </a>
                        
                        <a href = "https://en.wikipedia.org/wiki/Philippine_adobo" target = "_blank">
                            <div>
                            
                                <br>
                                <img src="chicken_adobo.jpeg" height = 100px width = 100px class = "centerPic">
                                <p class = "centerInsideText">
                                    CHICKEN<br>ADOBO
                                    <br><br>
                                    Unofficial national dish of the Philippines
                                </p>
                            </div>
                        </a>
    
                        
                        <a href = "https://en.wikipedia.org/wiki/Peanut_butter" target = "_blank">
                            <div>
                            
                                <br>
                                <img src="peanut_butter.jpg" height = 100px width = 100px class = "centerPic">
                                <p class = "centerInsideText">
                                    PB<br>SANDWICH
                                    <br><br>
                                    Versatile food of peanut butter spread on bread
                                </p>
                            </div>
                        </a>
                        
                        <a href = "https://en.wikipedia.org/wiki/Tempura" target = "_blank">
                            <div>
                                <br>
                                <img src="tempura.jpg" height = 100px width = 100px class = "centerPic">
                                <p class = "centerInsideText">
                                    TEMPURA<br>
                                    <br><br>
                                    Japanese dish coated shrimp
                                </p>
                            </div>
                        </a>
                        
                        <a href = "https://tl.wikipedia.org/wiki/Kalamares" target = "_blank">
                            <div>
                                <br>
                                <img src="calamares.jpg" height = 100px width = 100px class = "centerPic">
                                <p class = "centerInsideText">
                                    CALAMARES<br>
                                    <br><br>
                                    Deep-fried squid rings
                                </p>
                            </div>
                        </a>
   
                        <a href = "https://en.wikipedia.org/wiki/Onion_ring" target = "_blank">
                            <div>
                                <br>
                                <img src="onion_rings.jpg" height = 100px width = 100px class = "centerPic">
                                <p class = "centerInsideText">
                                    ONION<br>RINGS
                                    <br><br>
                                    Crispy fried rings of onions
                                </p>
                            </div>
                        </a>

                        <a href = "https://en.wikipedia.org/wiki/Sushi" target = "_blank">
                            <div>
                                <br>
                                <img src="sushi.jpg" height = 100px width = 100px class = "centerPic">
                                <p class = "centerInsideText">
                                    SUSHI<br>
                                    <br><br>
                                    Japanese dish of rolled vinegared rice
                                </p>
                            </div>
                        </a>
    
                        
                        <a href = "https://en.wikipedia.org/wiki/Pizza" target = "_blank">
                            <div>
                                <br>
                                <img src="pizza.jpg" height = 100px width = 100px class = "centerPic">
                                <p class = "centerInsideText">
                                    PIZZA<br>
                                    <br><br>
                                    Italian dish of baked doughy crust
                                </p>
                            </div>
                        </a>
                        
                        <a href = "https://en.wikipedia.org/wiki/Chicken_inasal" target = "_blank">
                            <div>
                                <br>
                                <img src="chicken_inasal.jpg" height = 100px width = 100px class = "centerPic">
                                <p class = "centerInsideText">
                                    CHICKEN<br>INASAL
                                    <br><br>
                                    Marinated chicken grilled to smoky perfection
                                </p>
                            </div>
                        </a>
    
                        <a href = "https://en.wikipedia.org/wiki/Pancit" target ="_blank">
                            <div>
                                <br>
                                <img src="pancit_canton.png" height = 100px width = 100px class = "centerPic">
                                <p class = "centerInsideText">
                                    PANCIT<br>CANTON
                                    <br><br>
                                    Filipino stir-fry dish symbol of long life
                                </p>
                            </div>
                        </a>
    
                        
    
                        
                    </div>
                </div>
            </div>
            
            
        </body>
    </head>






</html>
