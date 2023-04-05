<template>
  <div>
    <!-- Section: Design Block -->
    <section class="text-center">
      <!-- Background image -->
      <div class="p-5 bg-image"></div>
      <!-- Background image -->
      
      <div class="card mx-4 mx-md-5 shadow-5-strong" style=" margin-top: -100px; background: hsla(0, 0%, 100%, 0.8);backdrop-filter: blur(30px); ">
        <div class="info">
          <h1 class="display-1">Who am I?</h1>
		  <p class="lead shadow text-black my-5">I am an aspiring Web Developer with a keen interest in building projects to solve a need.
            What might that need be?
          </p>
		  <p class="lead shadow text-black">I specialize in Full Stack Development. This includes Front-End as well as Backend. </p>
          <p class="lead shadow text-black">
            In my free time you'll find me in front of a computer screen learning something new. Be it a Language, Programming language, Mathematics, Philosophy, Mythology or even Classical Literature. My favorite pass time is learning something new! 
            Even so, I still enjoy sports and any outdoor activity just to be closer to nature.
          </p>
		  <div class="row d-flex justify-content-center">
        <div class="col-lg-8">
	<div id="carouselExampleInterval" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-inner">
	<h3 class="display-3">DENO RAUTENBACH</h3>
    <div class="carousel-item active" data-bs-interval="10000">
      <img src="https://i.postimg.cc/k5cLyQhJ/DSC-0599-3-removebg-preview.png" class="d-block w-50 mx-auto" alt="...">
    </div>
    <div class="carousel-item" data-bs-interval="2000">
      <img src="https://i.postimg.cc/rsFtBJQh/DSC-0612-2-removebg-preview.png" class="d-block w-75 mx-auto" alt="...">
    </div>
    <div class="carousel-item">
      <img src="https://i.postimg.cc/C1kPQFzh/DSC-0601-2-removebg-preview.png" class="d-block w-50 mx-auto" alt="...">
    </div>
	<button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleInterval" data-bs-slide="prev">
    <span class="carousel-control-prev-icon bg-dark rounded-3" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleInterval" data-bs-slide="next">
    <span class="carousel-control-next-icon bg-dark rounded-3" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button> 
  </div>
</div>
      	</div>
    	</div>
		    <!-- button to services/form -->
			<button type="button" class="btn btn-outline-dark my-3"><router-link style="text-decoration:none" to="/contact">Let's Talk</router-link></button>
            <!-- list group -->
            <h1 class="shadow">Personal Details</h1>
            <ul class="list-group border-2 border-dark list-unstyled gap-2">
              <li class="list-group-item-dark rounded-2 p-2">9 March 2003</li>
              <li class="list-group-item-dark rounded-2 p-2">Tokai, Cape Town, 7966</li>
              <li class="list-group-item-dark rounded-2 p-2">Colored</li>
              <li class="list-group-item-dark rounded-2 p-2">No criminal record</li>
            </ul>
        </div>
  </div>
</section>
<!-- Section: Design Block -->
  </div>
</template>
<script>
export default{
  name: 'about'
}

</script>
<style scoped>
img {
	height: 50vh;
	object-fit: cover;
}
.bg-image{
  background-image: url('https://i.postimg.cc/wjhN4RB1/11718.jpg');
  background-repeat: no-repeat;
  background-size: cover;
  object-fit: cover;
  height: 300px;
  box-shadow: 0px 8px 8px 0px rgb(248, 186, 62) inset;
}

.pt-100{
    padding-top:100px;
}
.pb-100{
    padding-bottom:100px;
}
.section-title {
  margin-bottom: 60px;
}
.section-title p {
	color: #777;
	font-size: 16px;
}
.section-title h4 {
	text-transform: capitalize;
	font-size: 40px;
	position: relative;
	padding-bottom: 20px;
	margin-bottom: 20px;
	font-weight: 600;
}
.section-title h4:before {
	position: absolute;
	content: "";
	width: 60px;
	height: 2px;
	background-color: orangered;
	bottom: 0;
	left: 50%;
	margin-left: -30px;
}
.section-title h4:after {
	position: absolute;
	background-color: orangered;
	content: "";
	width: 10px;
	height: 10px;
	bottom: -4px;
	left: 50%;
	margin-left: -5px;
	border-radius: 50%;
}
ul.timeline-list {
	position: relative;
	margin: 0;
	padding: 0
}
ul.timeline-list:before {
	position: absolute;
	content: "";
	width: 2px;
	height: 100%;
	background-color: orangered;
	left: 50%;
	top: 0;
	-webkit-transform: translateX(-50%);
	        transform: translateX(-50%);
}
ul.timeline-list li {
	position: relative;
	clear: both;
	display: table;
}
.timeline_content {
	border: 2px solid orangered;
	background-color:#fff
}
ul.timeline-list li .timeline_content {
	width: 45%;
	color: #333;
	padding: 30px;
	float: left;
	text-align: right;
}
ul.timeline-list li:nth-child(2n) .timeline_content {
	float: right;
	text-align: left;
}
.timeline_content h4 {
	font-size: 22px;
	font-weight: 600;
	margin: 10px 0;
}
ul.timeline-list li:before {
	position: absolute;
	content: "";
	width: 25px;
	height: 25px;
	background-color: orangered;
	left: 50%;
	top: 50%;
	-webkit-transform: translate(-50%, -50%);
	        transform: translate(-50%, -50%);
	border-radius: 50%;
}
.timeline_content span {
	font-size: 18px;
	font-weight: 500;
	font-family: poppins;
	color: orangered;
}


</style>


