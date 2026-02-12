<template>
<div class="p-5 header-footer-custom text-center">
  <h1 class="display-4 fw-bold">Welcome to My Space</h1>
  <p class="lead text-white-50">Student | Creator | Dreamer</p>
</div>

<nav class="navbar navbar-expand-sm bg-dark navbar-dark sticky-top shadow">
  <div class="container-fluid">
    <ul class="navbar-nav mx-auto">
      <li class="nav-item"><a class="nav-link active" href="index.html">Profile</a></li>
      <li class="nav-item"><a class="nav-link" href="hobbies.html">Hobbies & Friends</a></li>
      <li class="nav-item"><a class="nav-link" href="resources.html">Resources</a></li>
      <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
    </ul>
  </div>
</nav>

<div class="container mt-5 mb-5">
  <div class="row align-items-center g-5">
    
    <div class="col-lg-6">
      <div id="profileCarousel" class="carousel slide shadow-lg profile-carousel themed-img overflow-hidden" data-bs-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="me1.jpg" class="d-block w-100" alt="Gabrielle Profile 1">
          </div>
          <div class="carousel-item">
            <img src="me2.jpg" class="d-block w-100" alt="Gabrielle Profile 2">
          </div>
          <div class="carousel-item">
            <img src="me3.jpg" class="d-block w-100" alt="Gabrielle Profile 3">
          </div>
          <div class="carousel-item">
            <img src="me4.jpg" class="d-block w-100" alt="Gabrielle Profile 4">
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#profileCarousel" data-bs-slide="prev">
          <span class="carousel-control-prev-icon"></span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#profileCarousel" data-bs-slide="next">
          <span class="carousel-control-next-icon"></span>
        </button>
      </div>
    </div>

    <div class="col-lg-6">
      <div class="content-card intro-section">
        <h2 class="display-5 mb-4">Hi, I'm Gabrielle!</h2>
        <p class="lead">I am a student at <b>Asia Pacific College</b>, currently navigating my way through the world of web programming and creative design.</p>
        <p>This website is a small window into my life—my support system, my furry companions, and the things that make me "shimmer." I love blending technical skills with my passion for DIY and crafting.</p>
        <hr class="my-4" style="border-color: #6a4c93; opacity: 0.2;">
        <p class="fst-italic text-muted">"To live for the hope of it all."</p>
        <div class="mt-4">
            <a href="hobbies.html" class="btn btn-primary px-4 py-2" style="background-color: #6a4c93; border: none; border-radius: 30px;">Explore My Hobbies</a>
        </div>
      </div>
    </div>

  </div>
</div>
</template>

<script></script>
<style src="./css/personalprofile.css"></style>