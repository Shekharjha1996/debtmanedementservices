<!DOCTYPE html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
  <title>DMS</title>
  <style>
    body {
      background: #232526;
      /* fallback for old browsers */
      background: -webkit-linear-gradient(to right, #414345, #232526);
      /* Chrome 10-25, Safari 5.1-6 */
      background: linear-gradient(to right, #414345, #232526);
      /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
    }

    .container {
      padding: 15px;
      margin: 0 auto;
      max-width: 768px;
    }

    .image {
      background-image: url("./photos/DMS_JPG.jpg");
      background-size: cover;
      background-repeat: no-repeat;
      background-position: center;
      width: 200px;
      height: 200px;
      border-radius: 50%;
      margin: 0 auto;
      border: 5px solid #fdf5e6;
    }

    .w3-border {
      border: 3px solid #ccc !important;
    }

    .links-container {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      gap: 20px;
      margin-top: 20px;
    }

    .links-container a {
      width: 100%;
      color: #414345 !important;
      transition: 0.2s;
      text-align: center;
    }

    .icons {
      display: flex;
      justify-content: center;
      gap: 10px;
      margin-top: 20px;
    }

    .icons a {
      text-decoration: none;
    }

    .icons a svg {
      fill: #fdf5e6 !important;
      transform: scale(1);
    }

    .contact {
      text-align: center;
      color: #fdf5e6;
      margin-top: 20px;
    }

    .contact .info {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      gap: 15px;
    }

    .contact .info span {
      display: flex;
      align-items: center;
      gap: 15px;
    }

    .bio {
      font-size: 11px;
      text-align: center;
    }

    @media screen and (max-width: 768px) {
      .image {
        width: 150px;
        height: 150px;
      }

      a {
        font-size: medium;
      }

      .profession span {
        font-size: 18px;
      }

      .bio {
        font-size: 13px;
      }
    }

    @media screen and (min-width: 768px) {
      .link {
        width: 100%;
      }
    }
  </style>
  <script src="https://unpkg.com/feather-icons@4.28.0/dist/feather.min.js"></script>
</head>
<body>
  <!-- Content container -->
  <div class="container">

    <!-- Image and

      <!-- Image and name container -->
      <div class="w3-margin-top" style="text-align: center">
        <div class="image w3-round"></div>
        <p class="profession"><span class="w3-padding w3-margin" style="font-weight: bolder; color: #fdf5e6">DEBT <span style="color: #ffcc66">MANAGEMENT SERVICES</span></span></p>
        <p class="bio"><span class="w3-padding w3-margin" style="font-weight: bolder; color: #fdf5e6"></span></p><br>
      </div>

      <!-- Links section 1 -->
      <div class="links-container">
        <a href="https://onlinerealsoft.com/Default.aspx" class="w3-button w3-sand w3-hover-pale-green link border" target="_blank">ADMIN LOGIN</a>
        <a href="https://onlinerealsoft.com/Default.aspx" class="w3-button w3-sand w3-hover-pale-green link border" target="_blank">EMPLOYEE LOGIN</a>
        <a href="./news.html" class="w3-button w3-sand w3-hover-pale-green link border" target="_blank">NEWS</a>
      </div>
      
      <!-- Links section 2 -->
      <div class="icons w3-padding">
        <a href="#" target="_blank">
          <i data-feather="facebook"></i>
        </a>
        <a href="#" target="_blank">
          <i data-feather="twitter"></i>
        </a>
        <a href="#" target="_blank">
          <i data-feather="linkedin"></i>
        </a>
        <a href="#" target="_blank">
          <i data-feather="github"></i>
        </a>
      </div><br>
      
        <div class="contact">
          <p class=""><span class="w3-padding w3-margin" style="font-weight: bolder; color: #fdf5e6">CONTACT US</span></p>
          <div class="info">
            <a href = "tel: +91 99713 73336"><span><i data-feather="phone"></i> +91 99713 73336</span></a>
            <a href = "tel: +91 73524 46646"><span><i data-feather="phone"></i> +91 73524 46646</span></a>            
            <a href = "mailto: debtmanagementservices2021@gmail.com"><span><i data-feather="mail"></i> debtmanagementservices2021@gmail.com</span></a>
          </div>
        </div><br>
        <div class="contact">
          <p class=""><span class="w3-padding w3-margin" style="font-weight: bolder; color: #fdf5e6">QUOTES</span></p>
          <img src="./photos/Employee-motivation-quotes_Bill-Gates.png" width="100%" height="250" frameborder="0" style="border:0"  allowfullscreen></iframe>
        </div>
 
          <div class="contact" style="position: absolute; top: 0; left: 2%; margin-top: 0px;">
          <p class=""><span class="w3-padding w3-margin" style="font-weight: bolder; color: #fdf5e6">EVENT CALENDER</span></p>
          <iframe src="https://calendar.google.com/calendar/embed?src=YOUR_CALENDAR_EMBED_LINK" style="border: 0" width="100%" height="250" frameborder="0" scrolling="no"></iframe>
          <p style="margin-top: 10px; font-weight: bold; color: #96f202;">May mahine ke 6, 7, 18 aur 24 ko week off rahega </p>
          </div>


        <div class="contact" style="position: absolute; top: 0; right: 5%;">
  <p class=""><span class="w3-padding w3-margin" style="font-weight: bolder; color: #fdf5e6">EMPLOYEE OF THE MONTH</span></p>
  <img src="./photos/rohit.jpg" width="100%" height="250" frameborder="0" style="border:0" allowfullscreen>
          <p style="margin-top: 10px; font-weight: bold; color: #96f202;">ROHIT SHARMA</p>
</div>
             
      <!-- Footer. This section contains an ad for W3Schools Spaces. You can leave it to support us. -->
      <footer class="w3-container w3-center w3-padding-48 w3-margin-top">
        <a class="w3-margin-bottom" href="https://dmsemployeemanagementsystem.w3spaces.com/index.html" title="This website was made with W3schools Spaces. Make your own free website today!" target="_blank">
          <img style="filter: brightness(0) invert(1);" src="./photos/DMS_JPG.jpg" alt="This website was made with W3schools Spaces. Make your own free website today!" width="50" height="50">
        </a> 
      <!-- End footer -->
      </footer>
      </div>

    </div>
    <script>
      feather.replace()
    </script>
  </body>  
</html>
