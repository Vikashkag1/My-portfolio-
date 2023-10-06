# My-portfolio-
About me and my project 
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Portfolio Website-vikash</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <!-- linking css file -->
  <link rel="stylesheet" href="style.css">
  <!-- bootstrap CDN -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
  <!-- font awesome -->
  <script src="https://kit.fontawesome.com/31149d48b0.js" crossorigin="anonymous"></script>
</head>

<body>
    <!-- navbar -->
    <nav class="navbar navbar-expand-lg fixed-top navbar-dark navbarScroll">
        <div class="container">
            <a class="navbar-brand" href="#">Vikash kag</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item active">
                        <a class="nav-link" href="#home">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about">About</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#skill">Skill</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#portfolio">Portfolio</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contact</a>
                    </li>
                </ul>
                
            </div>
        </div>
    </nav>
    <!-- main banner -->
    <section class="bgimage" id="home">
        <div class="container-fluid">
            <div class="row">
            <div class="col-lg-12 col-md-12 col-sm-12 col-xs-12 hero-text">
                <h2 class="hero_title">Hi, it's me vikash kag</h2>
                <p class="hero_desc">I am  living in Indore City</p>
            </div>
            </div>
        </div>
    </section>

    <!-- about section-->
    <section id="about">
        <div class="container mt-4 pt-4">
            <h1 class="text-center">About Me</h1>
            <div class="row mt-4">
                <div class="col-lg-4">
                    <img src="images/about.jpg" class= "imageAboutPage" alt="">
                </div>

                <div class="col-lg-8">
                    <p> I am vikash kag. I am  living in Indore. I am fresher to web Development.My technical skill is python. I did my graduation BSC (electronic & communication) from P.M.B. gujrati science college Indore. 
                        
                    </p>
                    <div class="row mt-3">
                        <div class="col-md-6">
                            <ul>
                                <li>Name: Vikash kag</li>
                                <li>Age: 28</li>
                                <li>Occupation:Student</li>

                            </ul>
                        </div>
                        <div class="col-md-6">
                            <ul>
                                <li>father's name: Mr. Laxman kag</li>
                                <li>mother's name:Mrs. Pushpa kag</li>
                                <li>contact:8349193446</li>
                                <li>Email: vikashkag095@gmail.com
                                </li>

                            </ul>
                        </div>
                    </div>
                    <div class="row mt-3">
                        <p>My best thing is that I learn things very quickly. And I have the curiosity to learn new things and adapt very easily to any environment.
                        </p>
                    </div>
                </div>
            </div>
    </section>

    <!-- services section-->
    <section id="services">
        <div class="container">
            <h1 class="text-center">Skill</h1>
            <div class="row">
                <div class="col-lg-4 mt-4">
                    <div class="card servicesText">
                        <div class="card-body">
                            <i class="fas servicesIcon fa-clock"></i>
                            <h4 class="card-title mt-3">python</h4>
                            <p class="card-text mt-3">I have completed my python from universal informatics Indore.I am certified to python. my learning duration 45 to 60 days.
                            </p>
                        </div>
                    </div>  
                </div>
                <div class="col-lg-4 mt-4">
                    <div class="card servicesText">
                        <div class="card-body">
                            <i class='fas servicesIcon fa-layer-group'></i>
                            <h4 class="card-title mt-3">R language</h4>
                            <p class="card-text mt-3">I am self taught R language and I have basic knowledge about it.
                            </p>
                        </div>
                    </div>  
                </div>

                <div class="col-lg-4 mt-4">
                    <div class="card servicesText">
                        <div class="card-body">
                            <i class='far servicesIcon fa-check-circle'></i>
                            <h4 class="card-title mt-3">Html ,CSS</h4>
                            <p class="card-text mt-3">I have basic knowledge about HTML and CSS. I know what are their uses and how  to use them in any website. HTML is basic structure of any website. and CSS adds beuty to it.
                            </p>
                        </div>
                    </div>  
                </div>
            </div>


    <!-- portfolio section-->
    <section id="portfolio">
        <div class="container mt-3">
            <h1 class="text-center">Project</h1>
            <div class="row">
                <div class="col-lg-4 mt-4">
                    <div class="card">
                        <img class="card-img-top" src="images/project 1.png" alt="Card image" style="width:100%">
                        <div class="card-body">
                            <h4 class="card-title">Project</h4>
                            <p class="card-text">I have created this website with the help of Google itself. this website is based on a resort </p>
                            <div class="text-center">
                                <a href="https://drive.google.com/file/d/1mCPjCDIFVT-h1HXeOByEJcyXcD7NTwzX/view?usp=share_link" class="btn btn-success">Link</a>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="col-lg-4 mt-4">
                    <div class="card portfolioContent">
                        <img class="card-img-top" src="images/project2.png" alt="Card image" style="width:100%">
                        <div class="card-body">
                            <h4 class="card-title">Dairy product website<form action=""></form></h4>
                            <p class="card-text">I have created this website with the help of youtube to watch this its portfolio vedio , touch the link button below:</p>
                            <div class="text-center">
                                <a href="https://drive.google.com/file/d/1PBxkHhjUa7yDEK_uNgtHPqSyhw5NsnVr/view?usp=share_link" class="btn btn-success">Link</a>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="col-lg-4 mt-4">
                    <div class="card portfolioContent">
                        <img class="card-img-top" src="images/project3.png" alt="Card image" style="width:100%">
                        <div class="card-body">
                            <h4 class="card-title">website</h4>
                            <p class="card-text">I have created this website with rendering method, to watch its portfolio video, touch the link button below.</p>
                            <div class="text-center">
                                <a href="https://drive.google.com/file/d/1RuCDv675wcF6CYA0fXrW5o__WWeYEt3A/view?usp=share_link" class="btn btn-success">Link</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <br>
            <div class="row">
                <div class="col-lg-4 mt-4">
                    <div class="card portfolioContent">
                        <img class="card-img-top" src="images/voice ass.jpg" alt="Card image" style="width:100%">
                        <div class="card-body">
                            <h4 class="card-title">my voice assistant program</h4>
                            <p class="card-text">I have made this program with the help of google, to watch this program click on the link button given below.</p>
                            <div class="text-center">
                                <a href="https://drive.google.com/file/d/1A8wbYX9sJL0-zDEtu6Lkxuvu6OCpwd5c/view?usp=share_link" class="btn btn-success">Link</a>
                            </div>
                        </div>
                    </div>
                </div>
<!-- 
                <div class="col-lg-4 mt-4">
                    <div class="card portfolioContent">
                        <img class="card-img-top" src="images/portfolioImage1.jpg" alt="Card image" style="width:100%">
                        <div class="card-body">
                            <h4 class="card-title">Twitter Clone</h4>
                            <p class="card-text">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
                            <div class="text-center">
                                <a href="#" class="btn btn-success">Link</a>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="col-lg-4 mt-4">
                    <div class="card portfolioContent">
                        <img class="card-img-top" src="images/portfolioImage4.jpg" alt="Card image" style="width:100%">
                        <div class="card-body">
                            <h4 class="card-title">Blog App</h4>
                            <p class="card-text">Lorem Ipsum is simply dummy text of the printing and typesetting industry.</p>
                            <div class="text-center">
                                <a href="#" class="btn btn-success">Link</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
    </section> -->

    <!-- contact section-->
    <section id="contact">
        <div class="container mt-3 contactContent">
            <h1 class="text-center">Contact Me</h1>

            <div class="row mt-4">
                <div class="col-lg-6">
                    <!-- to edit google map goto https://www.embed-map.com type your location, generate html code and copy the html  -->
                    <div style="max-width:100%;overflow:hidden;color:red;width:500px;height:500px;">
                        <div id="embedmap-canvas" style="height:100%; width:100%;max-width:100%;">
                            <iframe style="height:100%;width:100%;border:0;" frameborder="0" src="https://www.google.com/maps/embed/v1/place?q=indore&key=AIzaSyBFw0Qbyq9zTFTd-tUY6dZWTgaQzuU17R8">
                            </iframe>

                        </div>
                        <a class="googlemaps-html" href="" id="get-data-forembedmap">https://www.embed-map.com</a>
                        <style>#embedmap-canvas img{max-width:none!important;background:none!important;font-size: inherit;font-weight:inherit;}
                        </style>
                    </div>
                </div>


                <div class="col-lg-6">
                    <!-- form fields -->
                    <form>
                        <input type="text" class="form-control form-control-lg" placeholder="Name">
                        <input type="email" class="form-control mt-3" placeholder="Email">
                        <input type="text" class="form-control mt-3" placeholder="Subject">
                        <div class="mb-3 mt-3">
                            <textarea class="form-control" rows="5" id="comment" name="text" placeholder="Project Details"></textarea>
                        </div>
                    </form>
                    <button type="button" class="btn btn-success mt-3">Contact Me</button>
                    
                </div>

            </div>
        </div>
    </section>
    <!-- footer section-->
    <footer id="footer">
        <div class="container-fluid">
            <!-- social media icons -->
            <div class="social-icons mt-4">
                <a href="https://www.facebook.com/" target="_blank"><i class="fab fa-facebook"></i></a>
                <a href="https://www.instagram.com/" target="_blank"><i class="fab fa-instagram"></i></a>
                <a href="https://www.twitter.com/" target="_blank"><i class="fab fa-twitter"></i></a>
                <a href="https://www.linkedin.com/" target="_blank"><i class="fab fa-linkedin"></i></a>
                <a href="https://www.twitch.tv/" target="_blank"><i class="fab fa-twitch"></i></a>
            </div>
        </div>
    </footer>

    <!-- load javascript after loading all html content -->
    <script src="script/script.js"></script>

</body>

</html>

