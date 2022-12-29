<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <title>TinDog</title>
 <!-- BOOTSTRAP LINK -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
 <!-- Google fonts --> 
  <link rel="stylesheet" href="htpps://fonts.googleaps.com/css?family=Monteserrat|ubuntu" rel="stylesheet">
  <!-- CSS stylesheets  -->
  <script src="2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
  <link rel="stylesheet" href="style.css">
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
              <a class="nav-link" href="">Contact</a>
          </li>
          <li class="nav-item">
              <a class="nav-link" href="">Pricing</a>
          </li>
          <li class="nav-item">
              <a class="nav-link" href="">Download</a>
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

    <h2>I no longer have to sniff other dogs for love. I've found the hottest Corgi on TinDog. Woof.</h2>
    <img src="images/dog-img.jpg" alt="dog-profile">
    <em>Pebbles, New York</em>

    <!-- <h2 class="testimonial-text">My dog used to be so lonely, but with TinDog's help, they've found the love of their life. I think.</h2>
    <img class="testimonial-image" src="images/lady-img.jpg" alt="lady-profile">
    <em>Beverly, Illinois</em> -->

  </section>


  <!-- Press -->

  <section id="press">
    <img src="images/techcrunch.png" alt="tc-logo">
    <img src="images/tnw.png" alt="tnw-logo">
    <img src="images/bizinsider.png" alt="biz-insider-logo">
    <img src="images/mashable.png" alt="mashable-logo">

  </section>


  <!-- Pricing -->

  <section id="pricing">

    <h2>A Plan for Every Dog's Needs</h2>
    <p>Simple and affordable price plans for your and your dog.</p>


    <h3>Chihuahua</h3>
    <h2>Free</h2>
    <p>5 Matches Per Day</p>
    <p>10 Messages Per Day</p>
    <p>Unlimited App Usage</p>
    <button type="button">Sign Up</button>


    <h3>Labrador</h3>
    <h2>$49 / mo</h2>
    <p>Unlimited Matches</p>
    <p>Unlimited Messages</p>
    <p>Unlimited App Usage</p>
    <button type="button">Sign Up</button>


    <h3>Mastiff</h3>
    <h2>$99 / mo</h2>
    <p>Pirority Listing</p>
    <p>Unlimited Matches</p>
    <p>Unlimited Messages</p>
    <p>Unlimited App Usage</p>
    <button type="button">Sign Up</button>

  </section>


  <!-- Call to Action -->

  <section id="cta">

    <h3>Find the True Love of Your Dog's Life Today.</h3>
    <button type="button">Download</button>
    <button type="button">Download</button>

  </section>


  <!-- Footer -->

  <footer id="footer">

    <p>© Copyright TinDog</p>

  </footer>


</body>

</html>

/////////////////////////////////////////////////////////////////


CSS-
#title{
    background-color: #ff4c68;
    color: #fff;
}
.h1{
    font-family: "Montserrat-Black";
    font-size: 3.5rem;
    line-height: 1.5;
}
.h3{
    font-family:"Montserrat-Bold";
    font-size: 1.5rem;
}
.p{
    color: #8f8f8f;
}
.container-fluid{
    padding: 3% 15%;
}
/* navbar brand */
.navbar{
    padding-bottom: 4.5rem;
}
.navbar-brand{
    font-family:"ubuntu";
    font-size: 2.5rem;
    font-weight: bold;
}
.download-button{
    margin: 5% 3% 5% 0%
}

.title-image{
    transform: rotate(25deg);
    width:60%
}
#features{
    padding: 7% 15%;
}
.feature-box{
    text-align: center;
    padding: 5%;
}
.icon{
    color: #ef8172;
    margin-bottom: 1rem;
}
.icon:hover{
    color: #ff4c68;
}
