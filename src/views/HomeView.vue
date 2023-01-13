<template>
  <div class="home">
    <section class="landing-page my-5 ">
        <h1 class="display-1 fw-bold">Deno Rautenbach</h1>
      <h2 class="display-4 fw-bolder">Need help designing or building a website?</h2>
      <h3 class="display-5 fw-bolder">Look no further. Why? Because I am here...</h3>
    </section>
<!-- social icons -->
    <div>
      <div class="row">
        <ul id="social_icons" class="list-unstyled d-flex align-content-center justify-content-center gap-5">
          <li class="text-primary m-1"><a href="https://github.com/Simp4Hitagi/vue-portfolio"><i class="fa-brands fa-github fa-2x rounded"></i></a>Github</li>
          <li class="text-primary m-1"><a href="https://www.linkedin.com/feed/"><i class="fa-brands fa-linkedin fa-2x rounded"></i></a>LinkedIn</li>
          <li class="text-primary m-1"><a href=""><i class="fa-sharp fa-solid fa-2x fa-fire"></i></a>Firebase</li>
        </ul>
      </div>
    </div>
  </div>
  <Footer/>
</template>

<script>
import Footer from '@/components/Footer.vue';
export default {
  name: 'HomeView',
  components: {
    Footer
  }
}
</script>
