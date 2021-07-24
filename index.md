<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
    
    <!-- Bootstrap CSS -->
    <link href="css/bootstrap.min.css" rel="stylesheet" >
    <link rel="stylesheet" type="text/css" href = "css/style.css">

    <title>Assignment 2</title>
  </head>
  <body>

    <div class="header">
      <h2>AUST CSE</h2>
    </div>

    <!--Navigation-->
    <ul class="nav justify-content-center" id="navigation">
      <li class="nav-item">
        <a class="nav-link" href="#">HOMEPAGE</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">ABOUT</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">BOARD</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">SERVICES</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">BLOG</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">CONTACTS</a>
      </li>
      
    </ul>
    
    

<div id="carousel" class="carousel slide" data-bs-ride="carousel"> 
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="images/banner.jpg" class="d-block w-100" alt="...">
          <div class="carousel-caption d-none d-md-block">
            <div id="text1">Ahsanullah University of Science & Technology</div>
            <h1>CSE 3.1</h1>
          </div>
        </div>
        
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>

      <div class="container-fluid" id="contact-strip">
        <div class="row">
          <div class="col-md-4 ">
            <h5>CALL US 24/7</h5>
            <h3>123-456-7890</h3>
          </div>
          <div class="col-md-4 ">
            <h5>EMAIL ADDRESS</h5>
            <h3>example@example.com</h3>
          </div>
          <div class="col-md-4 ">
            <h5>OPEN HOURS</h5>
            <h3>Daily 9:00-20:00</h3>
          </div>
        </div>
      </div>

    </div>
    
    <div class="container-fluid" id="flashy">
      <div class="row justify-content-center">
        <div class="col-md-3 bg-white text-center m-3">
          <div class="outer_circle">
              <img src="images/icon1.png"class="rounded-circle"> 
          </div>
          <h5>Highly Secure</h5>
          <p>Cloud based services can offer our customers single tenant
            dedicated environments
          </p>
        </div>

        <div class="col-md-3 bg-white text-center m-3">
          <div class="outer_circle">
            <img src="images/icon2.png"class="rounded-circle"> 
        </div>
          <h5>True Cloud Sale</h5>
          <p>Working with customers making 100-40,000 hires per annum</p>
        </div>
        <div class="col-md-3 bg-white text-center m-3">
          <div class="outer_circle">
            <img src="images/icon3.png"class="rounded-circle"> 
        </div>
          <h5>Accurate Data</h5>
          <p>All of our customers data is validated. We build accurate data 
            banks for reporting.
          </p>
        </div>
      </div>
    </div>

    <!--cards-->
    <div class="container-fluid text-center" id="cards">
      <div class="row justify-content-center" id="card-id">
        <div class="col-lg-3">
            <div class="card">
                <div class="card-body">
                  <h2>About Us</h2>
                  Good content is everything. In a world that is oversaturated with content,
              you'll learn from successful writers and bloggers how to create content that matters and resonates 
              with your audience.
                </div>
            </div>
        </div>
        <div class="col-lg-3">
          <div class="card">
            <img class="card-img-top" src="images/grid1.jpg">
          </div>
      </div>
      <div class="col-lg-3">
        <div class="card">
            <div class="card-body">
              <h2>Our Strategy</h2>
              Sometimes the hardest part is knowing what to say and when to say it.
              At lines, you'll get the downlow on how to craft retweetable messages,
              when to post content, and what platforms you should be using.
            </div>
        </div>
    </div>  
    </div> <!--row1 ends-->
    <div class="row justify-content-center">
      <div class="col-lg-3">
        <div class="card">
          <img class="card-img-top" src="images/grid2.jpg">
        </div>
    </div>
    <div class="col-lg-3">
      <div class="card bg-dark">
          <div class="card-body">
            <h2>Our Mission</h2>
            Good content is everything. In a world that is oversaturated with content,
              you'll learn from successful writers and bloggers how to create content that matters and resonates 
              with your audience.
          </div>
      </div>
  </div>
  <div class="col-lg-3">
    <div class="card">
      <img class="card-img-top" src="images/grid3.jpg">
    </div>
  </div>

    </div><!--row2 ends-->
    </div> 
    <!--cards end here-->

    <!--blog posts-->
    <div class="container-fluid bg-white text-center" id="blogs">
      <h5>OUR</h5>
      <div class="blog-text">
        BLOG POSTS
      </div>
      <div class="row justify-content-center">
        <div class="col-lg-3"> <!--blog1-->
          <div class="card">
            <img class="card-img-top" src="images/blog1.jpg">
            <div class="card-body">
              <h4>Getting More for Your Money</h4>
              <p>The majority of businesses will have 
                a degree of reliance on recruitment suppliers...</p>
            </div>
            <div class="card-stats">
              <div class="stat">
                <div class="value">
                  <img src="images/icon4.png" style="width:70%"></div>
                <div class="type"><h6>EMMA</h6></div>
              </div> <!--stat div ends-->

              <div class="stat">
                <div class="value">
                  <img src="images/icon5.png" alt="" style="width:70%">
                </div>
                <div class="type">
                  <h6>AUGUST 6, 2017</h6>
                </div>
              </div><!--stat div ends-->
              <div class="stat">
                <div class="value">
                  <img src="images/icon6.png" alt="" style="width:70%">
                </div>
                <div class="type">
                  <h6>NEWS</h6>
                </div>
              </div><!--stat div ends here-->
            </div>
          </div>
        </div>
        <div class="col-lg-3"> <!--blog1-->
          <div class="card">
            <img class="card-img-top" src="images/blog2.jpg">
            <div class="card-body">
              <h4>Post With Youtube Video</h4>
              <p>Ribeye cupim jerky harm. Fatback sausage shoulder, 
                bresaola boudin hamburger pork turkey</p>
            </div>
            <div class="card-stats">
              <div class="stat">
                <div class="value">
                  <img src="images/icon4.png" style="width:70%"></div>
                <div class="type"><h6>EMMA</h6></div>
              </div> <!--stat div ends-->

              <div class="stat">
                <div class="value">
                  <img src="images/icon5.png" alt="" style="width:70%">
                </div>
                <div class="type">
                  <h6>June 10, 2017</h6>
                </div>
              </div><!--stat div ends-->
              <div class="stat">
                <div class="value">
                  <img src="images/icon6.png" alt="" style="width:70%">
                </div>
                <div class="type">
                  <h6>POST</h6>
                </div>
              </div><!--stat div ends here-->
            </div>
          </div>
        </div>
        <div class="col-lg-3"> <!--Blog3-->
          <div class="card">
            <img class="card-img-top" src="images/blog3.jpg">
            <div class="card-body">
              <h4>Post Format: Image</h4>
              <p>Beef beef ribs pancetta sirloin 
                tail brisket strip steak chuck swine frankfurter ham hock kielbasa</p>
            </div>
            <div class="card-stats">
              <div class="stat">
                <div class="value">
                  <img src="images/icon4.png" style="width:70%"></div>
                <div class="type"><h6>EMMA</h6></div>
              </div> <!--stat div ends-->

              <div class="stat">
                <div class="value">
                  <img src="images/icon5.png" alt="" style="width:70%">
                </div>
                <div class="type">
                  <h6>June 8, 2017</h6>
                </div>
              </div><!--stat div ends-->
              <div class="stat">
                <div class="value">
                  <img src="images/icon6.png" alt="" style="width:70%">
                </div>
                <div class="type">
                  <h6>NEWS</h6>
                </div>
              </div><!--stat div ends here-->
            </div>
          </div>
        </div>
      </div>

    </div>
    <!--blog posts ends here-->

    <!--copyright-->
    <div class="container-fluid bg-dark p-lg-5">
      <div class="copyright-text text-white text-center">
        &copy; Copyright 2021. All Rights Reserved
      </div>   
    </div>
    <!--copyright ends-->

    
    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="js/bootstrap.bundle.min.js"></script>

    
  </body>
</html>
