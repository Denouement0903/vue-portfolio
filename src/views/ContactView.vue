<template>
  <!-- <label class="mx-3 rounded-3 my-3">
    Your email:
    <input type="email" name="email" class="rounded-3">
  </label>
  <label class="mx-3 rounded-3 my-3">
    Your message:
    <textarea name="message" class="rounded-3"></textarea>
  </label> -->
    <div>
      <h1 class="display-1 fw-bold">Contact</h1>
        <form class="w-75 m-auto" action="https://formspree.io/f/xlevnzeq" method="POST">
          <div class="mb-3">
            <label for="exampleFormControlInput1" class="form-label">Name: </label>
            <input type="text" class="form-control" id="exampleFormControlInput1" placeholder="your name" required>
          </div>
          <div class="mb-3">
            <label for="exampleFormControlInput1" class="form-label">Surname: </label>
            <input type="text" class="form-control" id="exampleFormControlInput1" placeholder="your surname" required>
          </div>
          <div class="mb-3">
            <label for="exampleFormControlInput1" class="form-label">Email address</label>
            <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com" required>

          </div>
          <div class="mb-3">
            <label for="exampleFormControlTextarea1" class="form-label">Comments</label>
            <textarea class="form-control" id="exampleFormControlTextarea1" rows="3" name="message" required></textarea>
          </div>
          <button type="submit" class="btn btn-info">Submit</button>
        </form>
    </div>
    <Footer/>
</template>
<script>
import Footer from '@/components/Footer.vue';
export default {
    name: 'contact',
    components: {
      Footer
    }
}
</script>
<style scoped>
    
</style>