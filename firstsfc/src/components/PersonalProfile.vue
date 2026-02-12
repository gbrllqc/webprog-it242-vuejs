<template>
  <div class="profile-wrapper">
    <h1>Personal Profile Web page</h1>
    <p>About Me</p>

    <section class="info-content">
      <div class="bio">
        <p><strong>Name:</strong> Gabrielle Calibo</p>
        <p><strong>Nickname:</strong> Gab</p>
        <p><strong>Education:</strong> BSIT (St. Mary's Academy Pasay)</p>
        <p><strong>Goals:</strong> To be rich in money and health.</p>
      </div>

      <div class="main-image">
        <img src="https://wallpapers.com/images/featured-full/winnie-the-pooh-classic-1egcaz3zkdiirn2q.jpg" alt="pooh" class="featured-img">
      </div>
    </section>

    <div class="container gallery">
      <div class="gallery-item">
        <img src="https://i.pinimg.com/1200x/4a/07/87/4a07872c8029795ed887b5d9694c6001.jpg" alt="piglet">
      </div>
      <div class="gallery-item">
        <img src="https://i.pinimg.com/736x/52/e0/5e/52e05e268f1de4dd5f068f6c7cfef1e0.jpg" alt="eeyore">
      </div>
      <div class="gallery-item">
        <img src="https://i.pinimg.com/736x/cd/8b/e1/cd8be1d81b9d90630144c48f83baf6bf.jpg" alt="tigger">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'PersonalProfile'
}
</script>

<style src="./css/personalprofile.css"></style>