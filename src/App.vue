<template>
    <Navbar/>
    <div class="container-fluid min-vh-100">
      <router-view/>
    </div>
    <Footer/>
  </template>

<script>
import Navbar from './components/Navbar.vue';
import Footer from './components/Footer.vue';
export default {
  components: {
    Navbar, Footer
  }
}
</script>

<style>
@import url('https://fonts.cdnfonts.com/css/fox-on-the-run');
#app {
  font-family: 'Fox on the Run', sans-serif;
  font-size: 20px;
  color: black;
}

nav {
  padding: 30px;
}

/* nav a.router-link-active {
  color: #20de12;
} */

body {
  background-image: url('https://i.postimg.cc/VLmyvcpq/HD-wallpaper-yellow-wave-background-yellow-abstraction-wave-waves-background-creative-yellow-backgro.jpg');
  background-repeat: no-repeat;
  background-size: cover;
  object-fit: cover;
  overflow-x: auto;

}
</style>
