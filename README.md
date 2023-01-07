<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <title>TinDog</title>
 <!-- BOOTSTRAP LINK -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
  <!-- CSS stylesheets  -->
  <script src="2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
  <link rel="stylesheet" href="style.css">
  <link href="https://fonts.googleapis.com/css2?family=Rubik+Bubbles&display=swap" rel="stylesheet">
  <!-- google fonts -->
  <link href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin><link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,600;1,900&family=Ubuntu&display=swap" rel="stylesheet">
 <link  href="https://fonts.googleapis.com">
<link  href="https://fonts.gstatic.com" crossorigin>
  <!--Font awesome  -->
  <script src="https://kit.fontawesome.com/07aa7bb5c4.js" crossorigin="anonymous"></script>
</head>
<body>
  <section id="title">
    <div class="container-fluid">


    <!-- Nav Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark">
      <a class="navbar-brand" href="">tindog</a>
       <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
         <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <div class=top-right>
          <ul class="navbar-nav ms-auto mb-2 ">
          <li class="nav-item">
              <a class="nav-link" href="#footer">Contact</a>
          </li>
          <li class="nav-item">
              <a class="nav-link" href="#pricing">Pricing</a>
          </li>
          <li class="nav-item">
              <a class="nav-link" href="#cta">Download</a>
          </li>
      </ul>
    </div>
   </div>
  </nav>
    <!-- Title -->
    <div class="row">

    <div class="col-lg-6">
      <h1>Meet new and interesting dogs nearby.</h1>
      <button type="button" class="btn btn-dark btn-lg download-button"><i class="fa-brands fa-apple"></i> Download</button>
      <button type="button" class="btn btn-outline-light btn-lg download-button"><i class="fa-brands fa-google-play"></i>Download</button>
    </div>
    <div class="col-lg-6">
      <img class="title-image" src="images/iphone6.png" alt="iphone-mockup">
    </div>
  </div>
</div>

  </section>



  <!-- Features -->

  <section id="features">
  <div class="row">
  <div class="feature-box col-lg-4">
    <i class="icon fa-solid fa-circle-check fa-4x"></i>
    <h3>Easy to use.</h3>
    <p>So easy to use, even your dog could do it.</p>
  </div>
  <div class="feature-box col-lg-4">
    <i class="icon fa-solid fa-heart fa-4x"></i>
    <h3>Elite Clientele</h3>
    <p>We have all the dogs, the greatest dogs.</p>
  </div>
  <div class="feature-box col-lg-4">
    <i class="icon fa-solid fa-bullseye fa-4x"></i>
    <h3>Guaranteed to work.</h3>
    <p>Find the love of your dog's life or your money back.</p>
  </div>

  </div>

  </section>


  <!-- Testimonials -->

  <section id="testimonials">

    <div id="testimonial-carousel" class="carousel slide" data-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <h2>I no longer have to sniff other dogs for love. I've found the hottest Corgi on TinDog. Woof.</h2>
          <img class="testimonial-image" src="images/dog-img.jpg" alt="dog-profile">
          <em>Pebbles, New York</em>
        </div>
        <div class="carousel-item" >
          <h2 class="testimonial-text">My dog used to be so lonely, but with TinDog's help, they've found the love of their life. I think.</h2>
          <img class="testimonial-image" src="images/lady-img.jpg" alt="lady-profile">
          <em>Beverly, Illinois</em>
        </div>
      </div>
      <a class="carousel-control-prev" href="#testimonial-carousel" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon"></span>
      </a>
      <a class="carousel-control-next" href="#testimonial-carousel" role="button" data-slide="next">
    <span class="carousel-control-next-icon"></span>
      </a>
    </div>
  </section>


    <!-- <h2>I no longer have to sniff other dogs for love. I've found the hottest Corgi on TinDog. Woof.</h2>
    <img class="testimonial-image" src="images/dog-img.jpg" alt="dog-profile">
    <em>Pebbles, New York</em>

    <h2 class="testimonial-text">My dog used to be so lonely, but with TinDog's help, they've found the love of their life. I think.</h2>
    <img class="testimonial-image" src="images/lady-img.jpg" alt="lady-profile">
    <em>Beverly, Illinois</em> -->

  


  <!-- Press -->

  <section id="press">
    <img class="press-img" src="images/techcrunch.png" alt="tc-logo">
    <img class="press-img" src="images/tnw.png" alt="tnw-logo">
    <img class="press-img" src="images/bizinsider.png" alt="biz-insider-logo">
    <img class="press-img" src="images/mashable.png" alt="mashable-logo">

  </section>


  <!-- Pricing -->

  <section id="pricing">

    <h2>A Plan for Every Dog's Needs</h2>
    <p>Simple and affordable price plans for your and your dog.</p>

    <div class="row">

      <div class="pricing-col col-lg-4 col-md-6">
        <div class="card-deck">
          <div class="card-header">
              <h3>Chihuahua</h3>
          </div>
          <div class="card-Body">
            <h2>Free</h2>
            <p>5 Matches Per Day</p>
            <p>10 Messages Per Day</p>
            <p>Unlimited App Usage</p>
            <button class="btn btn-lg btn-block btn-outline-dark" type="button">Sign Up</button>
          </div>
      </div>

      </div>

      <div class="pricing-col col-lg-4 col-md-6">
        <div class="card-deck">
          <div class="card-header">
              <h3>Labrador</h3>
          </div>
          <div class="card-Body">
            <h2>$49 / mo</h2>
        <p>Unlimited Matches</p>
        <p>Unlimited Messages</p>
        <p>Unlimited App Usage</p>
        <button class= "btn btn-lg btn-block btn-outline-dark" type="button">Sign Up</button>
          </div>
      </div>
      </div>
  <!-- <div class="card-deck">
      <div class="card-header">
          <h3>Labrador</h3>
      </div>
      <div class="card-Body">
        <h2>$49 / mo</h2>
    <p>Unlimited Matches</p>
    <p>Unlimited Messages</p>
    <p>Unlimited App Usage</p>
    <button type="button">Sign Up</button>
      </div>
  </div> -->
  <div class="pricing-col col-lg-4">
    <div class="card-deck">
      <div class="card-header">
          <h3>Mastiff</h3>
      </div>
      <div class="card-Body">
        <h2>$99 / mo</h2>
        <p>Pirority Listing</p>
        <p>Unlimited Matches</p>
        <p>Unlimited Messages</p>
        <p>Unlimited App Usage</p>
        <button class="btn btn-lg btn-block btn-outline-dark" type="button">Sign Up</button>
          
      </div>
  </div>

  </div>
  
  <!-- <div class="card-deck">
      <div class="card-header">
          <h3>Mastiff</h3>
      </div>
      <div class="card-Body">
        <h2>$99 / mo</h2>
        <p>Pirority Listing</p>
        <p>Unlimited Matches</p>
        <p>Unlimited Messages</p>
        <p>Unlimited App Usage</p>
        <button type="button">Sign Up</button>
          
      </div>
  </div> -->


    <!-- <h3>Chihuahua</h3>
    <h2>Free</h2>
    <p>5 Matches Per Day</p>
    <p>10 Messages Per Day</p>
    <p>Unlimited App Usage</p>
    <button type="button">Sign Up</button> -->


    <!-- <h3>Labrador</h3>
    <h2>$49 / mo</h2>
    <p>Unlimited Matches</p>
    <p>Unlimited Messages</p>
    <p>Unlimited App Usage</p>
    <button type="button">Sign Up</button> -->


    <!-- <h3>Mastiff</h3>
    <h2>$99 / mo</h2>
    <p>Pirority Listing</p>
    <p>Unlimited Matches</p>
    <p>Unlimited Messages</p>
    <p>Unlimited App Usage</p>
    <button type="button">Sign Up</button> -->

  </section>


  <!-- Call to Action -->

  <section id="cta">

    <h3 class="cta-heading">Find the True Love of Your Dog's Life Today.</h3>
    <button type="button" class="btn btn-dark btn-lg download-button"><i class="fa-brands fa-apple"></i> Download</button>
    <button type="button" class="btn btn-outline-light btn-lg download-button"><i class="fa-brands fa-google-play"></i>Download</button>

  </section>


  <!-- Footer -->

  <footer id="footer">
    <i class="social-icon fa-brands fa-facebook"></i>
    <i class="social-icon fa-brands fa-twitter"></i>
    <i class="social-icon fa-brands fa-instagram"></i>
    <i class="social-icon fa-regular fa-envelope"></i>

    <p>© Copyright TinDog</p>

  </footer>
  <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.12.9/dist/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>


</body>

</html>



//CSS\\
#title{
    background-color: #ff4c68;
    color: #fff;
}
.h1{
    font-family: "Montserrat-Black", sans-serif;
    font-size: 3.5rem;
    line-height: 1.5;
}
h3{
    font-family: 'Montserrat', sans-serif;
    font-size: 1.5rem;
}

h2{
    font-family: 'Montserrat', sans-serif;
    font-size: 1.5rem;
    line-height: 1.5;
}
.p{
    color: #8f8f8f;
}
.container-fluid{
    padding: 3% 15% 7%;
}
/* navbar brand */
.navbar{
    padding-bottom: 4.5rem;
}
.navbar-brand{
    font-family: "'Ubuntu', sans-serif";
    font-size: 2.5rem;
    font-weight: bold;
}
.download-button{
    margin: 5% 3% 5% 0%
}

.title-image{
    transform: rotate(25deg);
    width:20%;
    position: absolute;
    top: 20px;
    right: 20%;
}
#features{
    padding: 7% 15%;
    background-color: #fff;
    position: relative;

}
.feature-box{
    text-align: center;
    padding: 4.5%;
}
.icon{
    color: #ef8172;
    margin-bottom: 1rem;
}
.icon:hover{
    color: #ff4c68;
}
/* testimonials */
#testimonials{
    text-align: center;
    background-color: #ef8172;
    color: #fff ;
}
.testimonial-image{
    width: 10%;
    border-radius: 100%;
}
#press{
    background-color: #ef8172;
    text-align: center;
    padding-bottom: 3%;
}
.press-img{
    width: 15%;
    margin: 20px 20px 50px;
}
.carousel-item{
    padding: 7% 15%;

}
#pricing{
   padding: 100px;
   text-align: center;
}
.pricing-col{
    padding: 3% 2%;
}
@media (max-width: 1028px){
    #title{
        text-align: center;
    }
    .title-image{
        position:static;
        transform:rotate(0);
    }
}
#cta{
    text-align: center;
    padding: 7% 15%;
    background-color: #ff4c68;
    color: #fff;
}
.cta-heading{
    font-family: "Montserrat-Black";
    
    font-size: 3.5rem;
    line-height: 1.5;
}
#footer{
    text-align: center;
    padding:2% 5% ;
    background-color: #fff;
}
.social-icon{
    margin: 20px 10px;
}
