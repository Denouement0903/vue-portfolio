<template>
    <Navbar/>


    <!-- <Footer/> -->
    <router-view/>
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
#app {
  font-family: 'Rowdies', cursive;
  text-align: center;
  color: #b30e02;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #7eb7f0;
}

nav a.router-link-exact-active {
  color: #20de12;
}

body {
  background-image: url("https://i.postimg.cc/c4xFqfnS/DALL-E-2023-01-12-11-54-06-neon-sunset-in-Cape-Town.png");
  background-repeat: no-repeat;
  background-position: 50% 50%;
  background-size: cover;
  object-fit: cover;

}
a:hover {
  background: #0509fc;
  border-radius: 15px;
}
@import url('https://fonts.googleapis.com/css2?family=Rowdies&display=swap');
</style>
