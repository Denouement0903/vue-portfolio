<template>
  <div>
    <section class="about">
      <h1 class="display-1 fw-bold">About Me</h1>
      <div id="con_about" class="container-fluid py-5 bg-secondary bg-opacity-50 h-100 my-5">
            <p class="lead shadow text-black my-5">I am an aspiring Web Developer with a keen interest in building projects to solve a need.
            What might that need be?
          </p>
          <p class="lead shadow text-black">I specialize in Full Stack Development. This includes Front-End as well as Backend. </p>
          <p class="lead shadow text-black">
            In my free time you'll find me in front of a computer screen learning something new. Be it a Language, Programming language, Mathematics, Philosophy, Mythology or even Classical Literature. My favorite pass time is learning something new! 
            Even so, I still enjoy sports and any outdoor activity just to be closer to nature.
          </p>
          <!-- button to services/form -->
          <button type="button" class="btn btn-outline-dark my-3"><router-link style="text-decoration:none" to="/contact">Let's Talk</router-link></button>
            <!-- list group -->
            <h1 class="shadow">Personal Details</h1>
            <ul class="list-group border-2 border-dark list-unstyled gap-2">
              <li class="list-group-item-dark rounded-2 p-2">9 March 2003</li>
              <li class="list-group-item-dark rounded-2 p-2">02 Tokai Road, Tokai Forest, Cape Town, 7945</li>
              <li class="list-group-item-dark rounded-2 p-2">Colored</li>
              <li class="list-group-item-dark rounded-2 p-2">No criminal record</li>
              <li class="list-group-item-dark rounded-2 p-2">0303095358089</li>
            </ul>
          </div>
    </section>
  </div>
  <Footer/>
</template>
<script>
import Footer from '@/components/Footer.vue';
export default{
components: {
  Footer
}

}

</script>
