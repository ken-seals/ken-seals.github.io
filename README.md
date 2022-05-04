Ken Seals
<!DOCTYPE html>
<html>
<head>
<title>Ken Seals</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body, h1,h2,h3,h4,h5,h6 {font-family: "Montserrat", sans-serif}
.w3-row-padding img {margin-bottom: 12px}
/* Set the width of the sidebar to 120px */
.w3-sidebar {width: 120px;background: #222;}
/* Add a left margin to the "page content" that matches the width of the sidebar (120px) */
#main {margin-left: 120px}
/* Remove margins from "page content" on small screens */
@media only screen and (max-width: 600px) {#main {margin-left: 0}}
</style>
</head>
<body class="w3-black">

<!-- Icon Bar (Sidebar - hidden on small screens) -->
<nav class="w3-sidebar w3-bar-block w3-small w3-hide-small w3-center">
  <!-- Avatar image in top left corner -->
  <img src="D585F34D-0708-44BD-AB3D-3936A1221E2E.JPEG" style="width:100%">
  <a href="#" class="w3-bar-item w3-button w3-padding-large w3-black">
    <i class="fa fa-home w3-xxlarge"></i>
    <p>HOME</p>
  </a>
  <a href="#about" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-user w3-xxlarge"></i>
    <p>ABOUT</p>
  </a>
  <a href="#photos" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-eye w3-xxlarge"></i>
    <p>PHOTOS</p>
  </a>
  <a href="#contact" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-envelope w3-xxlarge"></i>
    <p>CONTACT</p>
  </a>
</nav>

<!-- Navbar on small screens (Hidden on medium and large screens) -->
<div class="w3-top w3-hide-large w3-hide-medium" id="myNavbar">
  <div class="w3-bar w3-black w3-opacity w3-hover-opacity-off w3-center w3-small">
    <a href="#" class="w3-bar-item w3-button" style="width:25% !important">HOME</a>
    <a href="#about" class="w3-bar-item w3-button" style="width:25% !important">ABOUT</a>
    <a href="#photos" class="w3-bar-item w3-button" style="width:25% !important">PHOTOS</a>
    <a href="#contact" class="w3-bar-item w3-button" style="width:25% !important">CONTACT</a>
  </div>
</div>

<!-- Page Content -->
<div class="w3-padding-large" id="main">
  <!-- Header/Home -->
  <header class="w3-container w3-padding-32 w3-center w3-black" id="home">
    <h1 class="w3-jumbo"><span class="w3-hide-small">I'm</span> Ken Seals.</h1>
    <p>Photographer and Filmmaker.</p>
    <img src="D585F34D-0708-44BD-AB3D-3936A1221E2E.JPEG" style="width:100%">
  </header>

  <!-- About Section -->
  <div class="w3-content w3-justify w3-text-grey w3-padding-64" id="about">
    <h2 class="w3-text-light-grey">Ken Seals</h2>
    <hr style="width:200px" class="w3-opacity">
    <p>Ken Seals is a candidate for an associate of arts with a focus in AVMP from Howard Community College in Columbia, MD. She's assertive creative, full of passion. Ken creates in many mediums, such as photography, videography, cinematography, and writing. Once she starts a project she is determined to finish it, and finish it well. Even the comedy aspect of her art is well thought out and presented in its own unique way. Ken Seals desired to create her own worlds within this one by way of writing and filming. Editing videos is one of her pastimes. She enjoys working on videos and getting to see her final product. Ken loves the community of projects. The bonds that are made with the people you work with daily are something she appreciates even years after. Her high school experiences in the theater department have given her and advantage in larger productions. She has an eye for beauty in the little things. She can take a photo of nothing and make it something. Nothing is truly ugly to her. She can find the best out of the worst. She lives with small worlds of fantasy floating around in her head. Great ideas are never far from her mind. Ken loves being a part of something big and will always strive to be that way.
</p>
    <h3 class="w3-padding-16 w3-text-light-grey">My Skills</h3>
    <p class="w3-wide">Photography</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:95%"></div>
    </div>
    <p class="w3-wide">Film </p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:85%"></div>
    </div>
    <p class="w3-wide">Photoshop</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:80%"></div>
    </div><br>


    <button class="w3-button w3-light-grey w3-padding-large w3-section">
      <i class="fa fa-download">THE Resume.docx.pdf</i> Download Resume
    </button>

  <!-- Portfolio Section -->
  <div class="w3-padding-64 w3-content" id="photos">
    <h2 class="w3-text-light-grey">My Photos</h2>
    <hr style="width:200px" class="w3-opacity">

    <!-- Grid for photos -->
    <div class="w3-row-padding" style="margin:0 -16px">
      <div class="w3-half">
        <img src="fleur.jpg" style="width:100%">
        <img src="wedding.jpg" style="width:100%">
        <img src="wf.jpg" style="width:100%">
        <img src="ps.jpg" style="width:100%">
      </div>

      <div class="w3-half">
        <img src="love.jpg" style="width:100%">
        <img src="plane.jpg" style="width:100%">
        <img src="yikes.jpg" style="width:100%">
        <img src="ny.jpg" style="width:100%">
      </div>
    <!-- End photo grid -->
    </div>
  <!-- End Portfolio Section -->
  </div>

  <!-- Contact Section -->
  <div class="w3-padding-64 w3-content w3-text-grey" id="contact">
    <h2 class="w3-text-light-grey">Contact Me</h2>
    <hr style="width:200px" class="w3-opacity">

    <div class="w3-section">
      <p><i class="fa fa-map-marker fa-fw w3-text-white w3-xxlarge w3-margin-right"></i> Maryland, US</p>
      <p><i class="fa fa-envelope fa-fw w3-text-white w3-xxlarge w3-margin-right"> </i> Email: kenseals16@gmail.com</p>
    </div><br>
      </p>
    </form>
  <!-- End Contact Section -->
  </div>

    <!-- Footer -->
  <footer class="w3-content w3-padding-64 w3-text-grey w3-xlarge">
    <i class="fa fa-instagram w3-hover-opacity"></i>
    <i class="fa fa-youtube w3-hover-opacity"></i>
    <i class="fa fa-vimeo w3-hover-opacity"></i>
     <i class="fa fa-flickr w3-hover-opacity"></i>
  <!-- End footer -->
  </footer>

<!-- END PAGE CONTENT -->
</div>

</body>
</html>

</div>

</body>
</html>
