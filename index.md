<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MailGenius</title>
  <link href="https://fonts.googleapis.com/css2?family=PT+Sans:wght@400;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
  <link rel="stylesheet" href="css/slicknav.css">
  <link rel="stylesheet" href="css/style.css">
</head>

<body>
  <header class="header" data-aos="fade-down">
    <div class="container d-flex align-items-center">
      <a href="#" class="logo">
        <img src="img/logo.png" alt="logo">
      </a>
      <nav class="main-header-nav">
        <a href="#">Email Consulting</a>
        <a href="#">Contact Us</a>
      </nav>
      <nav class="info-header-nav">
        <a href="#">Privacy Policy</a>
        <a href="#">Disclaimer</a>
      </nav>
    </div>
    <!-- container -->
  </header>
  <!-- header -->
  <main class="main">
    <div class="inner">
      <div class="container">
        <div class="inner-call-to-action">
          <h1 class="inner-title" data-aos="fade-up">Send emails that don't end up in the spam folder</h1>
          <p class="inner-text" data-aos="fade-up" data-aos-delay="200">
            Find out if your email is likely to trigger spam filters. Run a <span>free</span> email spam and security
            test in <span>less than one minute.</span>
          </p>
          <div class="test-email" data-aos="fade-in" data-aos-delay="400">
            <button class="btn btn-default hvr-pulse-grow" >Test your email for free</button>
            <div class="email-not-required d-flex align-items-center justify-contant-center">
              <svg width="14" height="12" viewBox="0 0 14 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path
                  d="M4.75526 11.0149L0.205261 6.46494C-0.0680947 6.19159 -0.0680947 5.74837 0.205261 5.47499L1.19519 4.48504C1.46854 4.21166 1.91178 4.21166 2.18514 4.48504L5.25024 7.55011L11.8153 0.985046C12.0887 0.711691 12.5319 0.711691 12.8053 0.985046L13.7952 1.975C14.0686 2.24835 14.0686 2.69157 13.7952 2.96495L5.74521 11.015C5.47183 11.2883 5.02862 11.2883 4.75526 11.0149Z"
                  fill="#36A7B9" />
              </svg>
              <span>No Sign Up Required</span>
            </div>
          </div>
        </div>
        <!-- inner-call-to-action -->
        <div class="inner-services-wrap">
          <div class="container">
            <h3 class="inner-services-title" data-aos="fade-up" data-aos-delay="500">Our free email spam checker works with every email provider</h3>
            <div class="inner-services-list d-flex justify-contant-btw">
              <div 
              class="inner-service-item d-flex align-items-center justify-contant-center hvr-sweep-to-top"
              data-aos="fade-up" data-aos-delay="600">
                <img src="img/gmail-icon.svg" alt="">
              </div>
              <div 
              class="inner-service-item d-flex align-items-center justify-contant-center hvr-sweep-to-top"
              data-aos="fade-up" data-aos-delay="700">
                <img src="img/salesforce.svg" alt="">
              </div>
              <div 
              class="inner-service-item d-flex align-items-center justify-contant-center hvr-sweep-to-top"
              data-aos="fade-up" data-aos-delay="800">
                <img src="img/hubspot.svg" alt="">
              </div>
              <div 
              class="inner-service-item d-flex align-items-center justify-contant-center hvr-sweep-to-top"
              data-aos="fade-up" data-aos-delay="900">
                <img src="img/mailchimp.svg" alt="">
              </div>
              <div 
              class="inner-service-item d-flex align-items-center justify-contant-center hvr-sweep-to-top"
              data-aos="fade-up" data-aos-delay="1000">
                <img src="img/sendgrid.svg" alt="">
              </div>
              <div 
              class="inner-service-item d-flex align-items-center justify-contant-center hvr-sweep-to-top"
              data-aos="fade-up" data-aos-delay="1100">
                <img src="img/outlook-icon.svg" alt="">
              </div>
            </div>
          </div>
        </div>
        <!-- /.inner-services-wrap -->
 
      </div>
      <!-- /.container -->
     
    </div>
    <!-- inner -->
 
  </main>
  <!-- /.main -->

  <script src="https://code.jquery.com/jquery-3.5.1.min.js" integrity="sha256-9/aliU8dGd2tb6OSsuzixeV4y/faTqgFtohetphbbj0=" crossorigin="anonymous"></script>
<script src="js/jquery.slicknav.min.js"></script>
<script>
  $(function(){
      $('.header-nav').slicknav({
appendTo: '.header .container',
label: ''
      });
  });
</script>
<script src="https://unpkg.com/aos@next/dist/aos.js"></script>
<script>
  AOS.init();
</script>
</body>

</html>
