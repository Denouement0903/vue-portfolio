<template>
    <div>
        <form action="https://formspree.io/f/xlevnzeq" method="POST">
  <label class="mx-3 rounded-3 my-3">
    Your email:
    <input type="email" name="email" class="rounded-3">
  </label>
  <label class="mx-3 rounded-3 my-3">
    Your message:
    <textarea name="message" class="rounded-3"></textarea>
  </label>
  <!-- your other form fields go here -->
  <button type="submit" class="mx-3 rounded-3">Send</button>
</form>
    </div>
</template>
<script>
export default {
    name: 'contact'
}
</script>
<style scoped>
    
</style>