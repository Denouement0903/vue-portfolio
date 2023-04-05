<template>
    <div>
      <h1 class="display-1 fw-bold animate__animated animate__fadeInDown">Contact</h1>
<section class="mb-4">

<div class="row">
    <div class="col-md-9 mb-md-0 mb-5 my-auto d-block">
        <form id="contact-form" name="contact-form" action="https://formspree.io/f/xlevnzeq" method="POST">
            <div class="row">
                <div class="col-md-6">
                    <div class="md-form mb-0">
                        <input type="text" id="name" name="name" class="form-control">
                        <label for="name" class="">Your name</label>
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="md-form mb-0">
                        <input type="text" id="email" name="email" class="form-control">
                        <label for="email" class="">Your email</label>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-md-12">
                    <div class="md-form mb-0">
                        <input type="text" id="subject" name="subject" class="form-control">
                        <label for="subject" class="">Subject</label>
                    </div>
                </div>
            </div>
            <!--Grid row-->

            <!--Grid row-->
            <div class="row">

                <!--Grid column-->
                <div class="col-md-12">

                    <div class="md-form">
                        <textarea type="text" id="message" name="message" rows="2" class="form-control md-textarea"></textarea>
                        <label for="message">Your message</label>
                    </div>

                </div>
            </div>
            <div class="text-center text-md-left">
              <button type="submit" class="btn btn-info mb-3">Submit</button>
            </div>
        </form>

        <div class="status"></div>
    </div>
    <div class="col-md-3 text-center">
        <ul class="list-unstyled mb-0">
            <li><i class="fas fa-map-marker-alt fa-2x"></i>
                <p>Tokai 7966, Cape Town, SA</p>
            </li>

            <li><i class="fas fa-phone mt-4 fa-2x"></i>
                <p>+ 27 78 919 3011</p>
            </li>

            <li><i class="fas fa-envelope mt-4 fa-2x"></i>
                <p>denorauten@gmail.com</p>
            </li>
        </ul>
    </div>
    <!--Grid column-->

</div>

</section>
<!--Section: Contact v.2--> 
        <!-- <form class="w-75 m-auto" action="https://formspree.io/f/xlevnzeq" method="POST">
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
          <button type="submit" class="btn btn-info mb-3">Submit</button>
        </form> -->
    </div>
</template>
<script>
export default {
    name: 'contact'
}
</script>
<style scoped>
    
</style>