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
  },
  mounted() {
    AOS.init()
  },
}
</script>

<style>
@import url('https://fonts.cdnfonts.com/css/fox-on-the-run');
#app {
  background-color: black;
  font-family: 'Fox on the Run', sans-serif;
  font-size: 20px;
  color: white;
  overflow: hidden;
  cursor: crosshair;
}
::selection {
  color: rgb(255, 255, 255);
  background: rgb(69, 69, 69);
}

nav {
  padding: 30px;
}

::-webkit-scrollbar{
  display:none
}
</style>
