<!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" >
        
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>

        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <title>Index Page</title>
        
        <style>
            .content{
                min-height: 600px;
            }
            .banner-image{
                padding-bottom: 50px;
                margin-bottom: 20px;
                text-align: center;
                color: #f8f8f8;
                background: url(img/intro-bg_1.jpg) no-repeat center;
                background-size: cover;
            }
            .inner-banner-image{
                padding-top: 12%;
                width:80%;
                margin:auto;
            }
            .banner_content{
                position: relative;
                padding-top: 6%;
                padding-bottom: 6%;
                overflow:hidden;
                margin-bottom: 12%;
                background-color: rgba(0, 0, 0, 0.7);
                text-align: center;
            }
            .button{
                color: #fff;
                background-color: #c9302c;
                border-color: #ac2925;
                box-shadow: inset 0 3px 5px rgba(0, 0, 0, .125);
                padding: 10px 16px; 
                font-size: 18px;
                border-radius: 6px;
            }
            #footer{
                padding: 10px 0;
                background-color: #101010;
                color:#9d9d9d;
                bottom: 0;
                width: 100%;
            }
            h1{
                font: bold 60px AR DESTINE;
            }
            h5{
                font: italic normal 23px AvantGarde Md BT;
            }
        </style>
    </head>
    <body>
        <div class="navbar navbar-inverse">
            <div class="container">
                <div class="navbar-header">
                    <a class="navbar-brand" href="https://en.wikipedia.org/wiki/Lifestyle_(department_store)">Lifestyle Store</a>
                </div>
                <div>
                    <ul class="nav navbar-nav navbar-right">
                        <li><a href="signup.html"><span class="glyphicon glyphicon-user"></span> Sign Up</a></li>
                        <li><a href="login.html"><span class="glyphicon glyphicon-log-in"></span> Login</a></li>
                    </ul>
                </div>
            </div>
        </div>
        
        <div class="content">
            
            <center>
            
            <div class="banner-image">
                
                <div class="inner-banner-image">
                    
                    <div class="banner_content">
                        
                        <h1>We sell lifestyle</h1>
                        <h5>Flat 40% OFF on premium brands</h5>
                        <a href="product.html" class="button">Shop Now</a>
                        
                    </div>
                    
                </div>
                
            </div>
            
            </center>
            
        </div>
        
        <div class="container">
            
            <div class="row text-center" id="item list">
                
                <div class="col-sm-4">
                    
                    <a href="product.html#camera">
                        <div class="thumbnail">
                            <h3>Camera</h3>
                            <p>Chose among the best available in the world</p>
                            <img src="img/1.jpg" alt="Camera">
                        </div>
                    </a>
                    
                </div>
                
                <div class="col-sm-4">
                    
                    <a href="product.html#watches">

                        <div class="thumbnail">
                            <h3>Watches</h3>
                            <p>Original watches from the best brands</p>
                            <img src="img/7.jpg" alt="Watches">
                        </div>
                        
                    </a>
                    
                </div>
                
                <div class="col-sm-4">
                    
                    <a href="product.html#shirts">

                        <div class="thumbnail">
                            <h3>Shirts</h3>
                            <p>Our exquisite collection of shirts</p>
                            <img src="img/8.jpg" alt="Watches">
                        </div>
                        
                    </a>
                    
                </div>
                
            </div>
            
        </div>
        
    <center>
        
        <div id="footer">
            <footer>Copyright © Lifestyle Store. All Rights Reserved” and “Contact Us: +91 90000 00000</footer>
        </div>
    
    </center>
        
    </body>
</html>
