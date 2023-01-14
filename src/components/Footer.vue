<template>
  <div class="footer position-relative"> 
    <div class="position-absolute bottom-50">
      <ul id="social_icons" class="list-unstyled d-flex align-content-center justify-content-center gap-5 ">
        <li class="text-primary"><a href="https://github.com/Simp4Hitagi/vue-portfolio"><i class="fa-brands fa-github fa-2x rounded"></i></a>Github</li>
        <li class="text-primary"><a href="https://www.linkedin.com/feed/"><i class="fa-brands fa-linkedin fa-2x rounded"></i></a>LinkedIn</li>
        <li class="text-primary"><a href="https://www.facebook.com/profile.php?id=100081787963576"><i class="fa-brands fa-solid fa-2x fa-facebook"></i></a>Facebook</li>
      </ul>
    </div>
    <p class="lead mx-auto position-absolute bottom-0"><strong>Copyright &copy; 2023</strong></p>
  </div>
</template>
<script>
export default {
    name: 'footer'
}
</script>
<style scoped>
    .footer{
      background-image: url('https://i.postimg.cc/sD6kLdHS/DALL-E-2023-01-14-11-15-19-neon-sunset-in-Cape-Town.png');
      background-repeat: no-repeat;
      background-position: 50% 50%;
      background-size: cover;
      object-fit: cover;
      height: 32vh;
    }
</style>