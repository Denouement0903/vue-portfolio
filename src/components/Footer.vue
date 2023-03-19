<template>
  <div class="footer"> 
    <!-- Footer -->
<footer class="text-center text-lg-start bg-warning opacity-75 text-dark">
  <!-- Section: Social media -->
  <section class="d-flex justify-content-center text- justify-content-lg-center p-4 border-bottom">
    <!-- Left -->
    <!-- Right -->
    <div>
      <a href="" class="me-4 text-reset">
        <i class="fab fa-facebook-f"></i>
      </a>
      <a href="" class="me-4 text-reset">
        <i class="fab fa-instagram"></i>
      </a>
      <a href="" class="me-4 text-reset">
        <i class="fab fa-linkedin"></i>
      </a>
      <a href="" class="me-4 text-reset">
        <i class="fab fa-github"></i>
      </a>
    </div>
    <!-- Right -->
  </section>
  <!-- Section: Social media -->

  <!-- Section: Links  -->
  <section class="">
    <div class="container text-center text-md-start mt-5">
      <!-- Grid row -->
      <h6 class="text-uppercase text-center fw-bold mb-4">Contact</h6>          <!-- Links -->
      <div class="row mt-3 d-flex">
          <p><i class="fas fa-home me-3"></i> Cape Town, 02 Tokai Rd, Tokai, 7966</p>
          <p>
            <i class="fas fa-envelope me-3"></i>
            denorauten@gmail.com
          </p>
          <p><i class="fas fa-phone me-3"></i> + 27 919 3011</p>
        <!-- Grid column -->
      </div>
      <!-- Grid row -->
    </div>
  </section>
  <!-- Section: Links  -->

  <!-- Copyright -->
  <div class="text-center p-4" style="background-color: rgba(0, 0, 0, 0.05);">
    <a href="/">{{year}} &#169; Copyright Deno Rautenbach</a>  
  </div>
  <!-- Copyright -->
</footer>
<!-- Footer -->
  </div>
</template>
<script>
export default {
    name: 'footer',
    data() {
        return {
            year: new Date().getFullYear()
        }
    }
}
</script>
<style scoped>
</style>