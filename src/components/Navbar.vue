<template>
    <div>
        <nav class="navbar navbar-expand-lg bg-primary-subtle">
            <div class="container-fluid bs-primary-bg-subtle">
              <a class="navbar-brand" href="#"><img src="https://i.postimg.cc/xCZBBMwP/icons8-d-64.png" alt=""></a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                  <li class="nav-item p-3">
                    <router-link  to="/">Home</router-link>
                  </li>
                  <li class="nav-item p-3">
                    <router-link to="/about">About</router-link>
                  </li>
                  <li class="nav-item p-3">
                    <router-link to="/resume">Resume</router-link>
                  </li>
                  <li class="nav-item p-3">
                    <router-link to="/projects">Projects</router-link>
                  </li>
                  <li class="nav-item p-3">
                    <router-link to="/testimonials">Testimonials</router-link>
                  </li>
                  <li class="nav-item p-3">
                    <router-link to="/contact">Contact</router-link>
                  </li>
                </ul>
              </div>
            </div>
          </nav>
    </div>
</template>
<script>
export default {
    name: 'navbar'
}
</script>
<style scoped>
    nav {
      background-image: url('https://i.postimg.cc/k4fh13x0/DALL-E-2023-01-10-13-32-20-neon-sunset-in-Cape-Town.png');
    }
</style>