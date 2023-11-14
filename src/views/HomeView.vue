<template>
	<header>
		<div>
			<nav class="navbar navbar-expand-lg fixed-top bg-black opacity-50">
			  <div class="container-fluid">
				<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
				  <span class="navbar-toggler-icon"></span>
				</button>
				<div class="collapse navbar-collapse" id="navbarNavAltMarkup">
				  <div class="navbar-nav mx-auto my-2">
					<a style="text-decoration:none" class="nav-link active text-light" aria-current="page"  href="/">Home</a>
					<a style="text-decoration:none" class="nav-link text-light" href="#about">About</a>
					<a style="text-decoration:none" class="nav-link text-light" href="#resume">Resume</a>
					<a style="text-decoration:none" class="nav-link text-light" href="#projects">Projects</a>
					<a style="text-decoration:none" class="nav-link text-light" href="#testimonials">Testimonials</a>
					<a style="text-decoration:none" class="nav-link text-light" href="#contact">Contact</a>
				  </div>
				</div>
			  </div>
			</nav>
		  </div>
	</header>
	<main class="min-vh-100">
		<!-- Home-->
		<section id="home" class="home my-5 py-5">
		  <div class="container-fluid-mouse" style="height: 800px">
			<div class="row d-flex align-items-center text-center field">
				<div id="welcome" class="my-5">
					<h1 class="welcome display-1 text-light my-3">Hello</h1>
					<h1 class="welcome display-1 text-light my-3">Welcome</h1>
					<h1 class="welcome display-1 text-light my-3">Hi</h1>
				  </div>
				  <div class="mouse"></div>
			</div>
		  </div>
		</section>
	  
		<!-- About -->
	    <section id="about" class="text-center my-5 py-5">
			<!-- Background image -->
			<div class="p-5 bg-image"></div>
			<!-- Background image -->
			
			<div class="roses-about text-light mx-4 mx-md-5 shadow-5-strong">
			  <div class="info">
				<h1 class="display-1">Who am I?</h1>
				<p class="lead text-light my-5">I am an aspiring Web Developer with a keen interest in building projects to solve a need.
				  What might that need be?
				</p>
				<p class="lead text-light">I specialize in Full Stack Development. This includes Front-End as well as Backend. </p>
				<p class="lead text-light">
				  In my free time you'll find me in front of a computer screen learning something new. Be it a Language, Programming language, Mathematics, Philosophy, Mythology or even Classical Literature. My favorite pass time is learning something new! 
				  Even so, I still enjoy sports and any outdoor activity just to be closer to nature.
				</p>
				<div class="row d-flex justify-content-center">
			  <div class="col-lg-8">
		  <div id="carouselExampleInterval" class="carousel slide" data-bs-ride="carousel">
		<div class="carousel-inner">
		  <h3 class="display-3">DENO RAUTENBACH</h3>
		  <div class="carousel-item active" data-bs-interval="10000">
			<img src="https://i.postimg.cc/5yDCYYsr/Microsoft-Teams-image-20.jpg" class="rounded-3 d-block w-50 mx-auto h-50" alt="...">
		  </div>
		</div>
	  </div>
				</div>
			  </div>
				  <!-- button to services/form -->
				  <button type="button" class="btn btn-outline-dark my-3"><a style="text-decoration:none" class="text-light" href="#contact">Let's Talk</a></button>
				  <!-- list group -->
				  <h1 class="shadow">Personal Details</h1>
				  <ul class="list-group border-2 border-dark list-unstyled gap-2">
					<li class="list-group-item-dark rounded-2 p-2"> 09 // 03 // 2003</li>
					<li class="list-group-item-dark rounded-2 p-2">Tokai, Cape Town</li>
					<li class="list-group-item-dark rounded-2 p-2">Colored</li>
					<li class="list-group-item-dark rounded-2 p-2">No criminal record</li>
				  </ul>
			  </div>
		</div>
	  	</section>
	  <!-- Resume -->
	  	<section id="resume" class="resume my-5 py-5">
			  <h1 class="display-1">Explore my Resume</h1>
		  <div class="container-fluid">
			<div class="row  rounded-2">
			  <div class="col-md-6">
				   <h3 class="progress-title">WordPress</h3>
				   <div class="progress w-blue">
					   <div class="progress-bar" style="width:70%;">
						   <div class="progress-value">70%</div>
					   </div>
				   </div>
				   <h3 class="progress-title">HTML5</h3>
				   <div class="progress orange">
					   <div class="progress-bar" style="width:95%;">
						   <div class="progress-value">95%</div>
					   </div>
				   </div>
				   <h3 class="progress-title">CSS3</h3>
				   <div class="progress blue">
					   <div class="progress-bar" style="width:89%;">
						   <div class="progress-value">89%</div>
					   </div>
				   </div>
			
				   <h3 class="progress-title">JS</h3>
				   <div class="progress yellow">
					   <div class="progress-bar" style="width:72%;">
						   <div class="progress-value">72%</div>
					   </div>
				   </div>
				   <h3 class="progress-title">VUEJS</h3>
				   <div class="progress green">
					   <div class="progress-bar" style="width:79%;">
						   <div class="progress-value">79%</div>
					   </div>
				   </div>
				   <h3 class="progress-title">MySQL</h3>
				   <div class="progress light-blue">
					 <div class="progress-bar" style="width:91%;">
					  <div class="progress-value">91%</div>
					</div>
				  </div>
				  <h3 class="progress-title">BOOTSTRAP</h3>
				  <div class="progress purple">
					<div class="progress-bar" style="width:93%;">
					  <div class="progress-value">93%</div>
					</div>
				  </div>
				  <h3 class="progress-title">REACTJS</h3>
				  <div class="progress r-blue">
					  <div class="progress-bar" style="width:50%;">
						  <div class="progress-value">50%</div>
					  </div>
				  </div>
				   <h3 class="progress-title">NODEJS</h3>
				   <div class="progress dark-green">
					   <div class="progress-bar" style="width:69%;">
						   <div class="progress-value">69%</div>
					   </div>
				   </div>
				   <h3 class="progress-title">PYTHON</h3>
				   <div class="progress dark-yellow">
					   <div class="progress-bar" style="width:57%;">
						   <div class="progress-value">57%</div>
					   </div>
				   </div>
			   </div>
			   <div class="col-md-6 my-5">
				<h2 class="text-center display-1 text-light">SKILLS</h2>
				<img class="w-75 rounded-5 mx-auto my-5 d-block" src="https://i.postimg.cc/jdGp9qzx/lil-nas-x-typing.gif" alt="">
				<h4 class="display-5 text-center text-light">Download my CV</h4>
				<button type="button" class="btn btn-light rounded-2 mx-auto d-block my-5 text-black">
				  <a target="_blank" class="text-dark" :href="downloadURL" download>Download</a>
				  </button>
			   </div>
			</div>
			</div>
			<div class="work-education opacity-75 my-5 rounded-2">
			  <section class="experience pt-100 pb-100" id="experience">
		<div class="container-fluid">
		  <div class="row">
			<div class="col-xl-8 mx-auto text-center">
			  <div class="section-title">
				<h4 class="text-light">Education and Experience</h4>
				<h5 class="animate__animated animate__fadeInUp">Let's take a trip down memory lane...</h5>
			  </div>
			</div>
		  </div>
		  <div class="row">
				   <div class="col-xl-12">
					  <ul class="timeline-list">
						 <!-- Single Experience -->
						 <li>
							<div data-aos="fade-right" data-aos-offset="300" data-aos-easing="ease-in-sine" class="timeline_content">
							   <span>15 Jan 2017</span>
							   <h1>Student</h1>
							   <h4>Start of Highschool</h4>
							   <p>I started grade 8 at <span class="font-weight-bold">Villiersdorp Secondary School.</span> I matriculated with a Bachelors pass. 
								My Subjects Included:
								<em>Afrikaans HL,
								English FAL,
								Maths,
								Life Sciences,
								Geography,
								Computer Applications Technology,
								Life Orientation</em>
							  </p>
							  <span>Dec 2021</span>
							   <h4>End Of Highschool</h4>
							   <p>I was Best in Afrikaans and English, 2nd best in Math, Geography and Computer Applications Technology, 3rd best in Life Science and achieved a distinction in English FAL in 2021 for Matric.</p>
							</div>
						 </li>
						 
							  <li>
							<div data-aos="fade-left" data-aos-offset="300" data-aos-easing="ease-in-sine" class="timeline_content">
							  <span>11 Feb 2022</span>
							  <h1>Assistant</h1>
							   <h4>Start of Job</h4>
							   <p>I acquired my first hands-on job experience at a company called <span class="font-weight-bold">Tech Nasty.</span> During my time at Tech Nasty my designation was as an assistant in Information Technology and Computer repair. This involved <em>troubleshooting of hardware and software issues and repair</em> as well as <em>selling of technology and services.</em> My key responsibilities included shop management and assistance.</p>
	  
							   <span>15 Mar 2021</span>
							   <h4>End of Job</h4>
							   <p>My reason for leaving was the indefinite closure of Tech Nasty due to the restrictions brought forth by the Covid-19 pandemic at the time. Also another contributing factor was that I was self-studying and it was in the time of me having remote classes as well as working at the aforementioned company simultaneously.</p>
							</div>
						 </li>
						 
						 <li>
							<div data-aos="fade-right" data-aos-offset="300" data-aos-easing="ease-in-sine" class="timeline_content">
							  <span>27 Sep 2022</span>
							  <h1>Web Dev Graduate</h1>
							   <h4>Start of Studies</h4>
							   <p>I attended a 6-month long coding boot camp at <span class="font-weight-bold">Life Choices Academy </span> where I acquired various skills with projects to solidify the knowledge and along with it, <em>Work Ethics, Soft skills and Personal/Professional development.</em></p>
	  
							   <span>31 Mar 2023</span>
							   <h4>End of Studies</h4>
							   <p>My time at Life Choices Academy ended when I completed the Full-Stack Web development course.</p>
							</div>
						 </li>
						 <li>
							<div data-aos="fade-left" data-aos-offset="300" data-aos-easing="ease-in-sine" class="timeline_content">
							  <span>Apr 2023 - Present</span>
							  <h1>Assistant Lecturer / Studio Intern</h1>
							   <h4>Start of Role</h4>
							   <p>I am currently serving as a technical lecturer assistant at <span class="font-weight-bold">Life Choices Academy </span> while simulteneously upskilling in <span class="font-weight-bold">Life Choices Studio </span>. My duties at the LC Academy include assisting with the lessons, planning schedules, keeping up to date with the relevant study material as well as guideing students in writing code and doing projects. At the same time I am learning a multitude of new technology's in LC Studio.</p>
							</div>
						 </li>
					  </ul>
				   </div>
				</div>
		</div>
		</section>
			</div>
		</section>
	  <!-- Projects -->
	  <section id="projects" class="my-5 py-5">
		  <h1 class="display-1 fw-bold animate__animated animate__fadeInDown">Projects</h1> 
		  <div class="container">
			  <div class="row">
					  <div class="col" v-for="project in projectsArray" :key="project">
						  <div class="card mx-auto my-3 border border-dark border-4 " style="width: 18rem;">
								  <img :src=project.image class="card-img-top" alt="..." style="height: 13rem;">
								  <div class="card-body border-4 bg-black">
									<h5 class="card-title">{{project.name}}</h5>
									<p class="card-text">{{project.description}}</p>
									<a :href=project.hosted class="btn btn-light border-dark mx-3"  target="_blank">Hosted</a>
									<a :href=project.github class="btn btn-light border-dark mx-3"  target="_blank">Github</a>
								  </div>
							</div>
					  </div>
			  </div>
		  </div>
		  <!-- python terminal -->
		  <!-- <div ref="terminalContainer"></div> -->
	  </section>
	  
	  <!-- Testimonials -->
	  <section id="testimonials" class="testimonials my-5 py-5">
		<h1 class="display-1 fw-bold animate__animated animate__fadeInUp">Testimonials</h1> 

		<div class="container-testimonials">
			<div class="row">
					<div class="col" v-for="testimonial in testimonialsArray" :key="testimonial">
						<div class="card mx-auto my-3 " style="width: 22rem;">
								<img :src=testimonial.image class="card-img-top" alt="..." style="height: 13rem;">
								<div class="card-body border-4 bg-black" style="height: 36rem;">
								  <h5 class="card-title">{{testimonial.name}}</h5>
								  <p class="card-text ">{{testimonial.title}}</p>
								  <p class="card-text my-auto" style="height: 20rem;">{{testimonial.testimonial}}</p>
								</div>
						  </div>
					</div>
			</div>
		</div>
	  </section>
	  
	  <!-- Contact -->
	  <section id="contact" class="my-5 py-5">
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
				  <button type="submit" class="btn btn-dark mb-3">Submit</button>
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
	  </div>
	  
	  </section>
	  
	  </section>
	</main>
	<footer>

	</footer>
</template>


<script>
// create a backend for projects
import { Terminal } from 'xterm';
import { FitAddon } from 'xterm-addon-fit';
export default {
  name: 'HomeView',
  mounted() {
	const links = document.querySelectorAll('ul.nav li a[href^="#"]');

links.forEach(link => {
  link.addEventListener('click', (event) => {
	event.preventDefault();
	const target = document.querySelector(link.hash);
	const offsetTop = target.offsetTop;

	window.scrollTo({
	  top: offsetTop,
	  behavior: "smooth"
	});
  });
});
    window.addEventListener('scroll', this.scrollFunction);
	AOS.init();
	const terminalContainer = this.$refs.terminalContainer;
        const term = new Terminal();
        const fitAddon = new FitAddon();
    
        term.loadAddon(fitAddon);
        term.open(terminalContainer);
        fitAddon.fit();
    
        // You can now use `term` to interact with the terminal
        term.write('Hello, world!\r\n');
  },
  beforeUnmount() {
    window.removeEventListener('scroll', this.scrollFunction);
  },
  methods: {
    scrollFunction() {
      const landingPageElement = document.getElementsByClassName("home")[0];
      if (document.body.scrollTop > 50 || document.documentElement.scrollTop > 50) {
        landingPageElement.style.backgroundImage = "url('https://i.postimg.cc/mZvPzvWg/Dark-Woods-Wallpaper.jpg')";
        // landingPageElement.style.fontSize = "30px";
      } else {
        landingPageElement.style.backgroundImage = "url('https://i.postimg.cc/G3fCHWfS/forest20.jpg')";
        // landingPageElement.style.fontSize = "90px";
      }
    }
  },
  data() {
    return {
		projectsArray: [
                {
                    id: 1,
                    name: "Manga Site",
                    description: "A E-commerce project using VUEJS and NODE JS and API Functionality",
                    image: "https://i.postimg.cc/yxs7RY5z/Screenshot-2023-03-28-161820.png",
                    hosted: "https://mangako-deno-rautenbach.netlify.app/",
                    github: "https://github.com/Simp4Hitagi/Capstone-Mangako"
                },
                {
                    id: 2,
                    name: "Figures Site",
                    description: "A collaborative E-commerce project using VUEJS and NODE JS",
                    image: "https://i.postimg.cc/DwMsPtnN/Screenshot-2023-03-28-162401.png",
                    hosted: "",
                    github: "https://github.com/Simp4Hitagi/Otaku"
                },
                {
                    id: 3,
                    name: "Calculator",
                    description: "A basic calculator app built using HTML, CSS, Bootstrap and Javascript",
                    image: "https://i.postimg.cc/fbN8V6q4/calculator.png",
                    hosted: "https://deno-calculator.netlify.app",
                    github: "https://github.com/Simp4Hitagi/My_Calculator"
                },
                {
                    id: 4,
                    name: "Vue Portfolio",
                    description: "A updated of the current portfolio project using Vue, JS, HTML and CSS ",
                    image: "https://i.postimg.cc/gcTMrB6g/Screenshot-2023-03-28-162020.png",
                    hosted: "https://deno-vue-portfolio.netlify.app/",
                    github: "https://github.com/Simp4Hitagi/vue-portfolio"
                },
                {
                    id: 5,
                    name: "Point of Sale System",
                    description: "E-Commerce ste with a CRUD system primarily built using JS, HTML and CSS",
                    image: "https://i.postimg.cc/cH96MZhK/pos-system.png",
                    hosted: "https://deno-pos.netlify.app/index.html",
                    github: "https://github.com/Simp4Hitagi/PointOfSale_System"
                },
                {
                    id: 6,
                    name: "WordPress E-Commerce site",
                    description: "A collabaritive E-Commerce site built using WordPress and it's extensions",
                    image: "https://i.postimg.cc/tRB8VCRV/Screenshot-4.png",
                    hosted: "https://dev-triptronik.pantheonsite.io/",
                    github: ""
                },
                {
                    id: 7,
                    name: "Portfolio",
                    description: "My first Portfolio project using HTML, CSS and Bootstrap",
                    image: "https://i.postimg.cc/cJ2qxRPr/portfolio.png",
                    hosted: "https://deno-portfolio1.netlify.app",
                    github: "https://github.com/Simp4Hitagi/Final_Portfolio_Project"
                },


                
                {
                    id: 8,
                    name: "Python Projects",
                    description: "A few projects I created in Python while i was self-studying.",
                    image: "https://i.postimg.cc/q7QxMh26/python-logo.png",
                    hosted: "",
                    github: "https://github.com/Simp4Hitagi/Python-Projects"
                },
                {
                    id: 9,
                    name: "News API Site",
                    description: "A website that pulls data from a free NewsAPI using Recat.JS",
                    image: "https://i.postimg.cc/tJKk6KrK/Screenshot-2.png",
                    hosted: "https://bnry-test.vercel.app",
                    github: "https://github.com/Simp4Hitagi/BNRY-Test"
                },

            ],
		testimonialsArray: [
                {
                    name: "Joel Mukanya",
                    title: "LC Lecturer",
                    testimonial: "Deno is a very creative, go-getter, and well-behaved student. He does enjoy working with his classmates and works well on his project. He has gained knowledge of web development, including Bootstrap 5. I will be very delighted to see him get hired as a developer.",
                    image: "https://i.postimg.cc/NMP354mT/Joel-Profile-removebg-preview.png"
                },
                {
                    name: "KonkeJeff RicardoMalindi",
                    title: "Intern Developer",
                    testimonial: "Deno is like a sponge, constantly absorbing knowledge and has a very keen interest in finding out the salution to a problem he has no idea how to solve,that is why in work space he would be a very resourceful asset",
                    image: "https://i.postimg.cc/NF6ykpY9/Konke-removebg-preview.png"
                }, 
                {
                    name: "Umayr Nordien",
                    title: "Intern Developer",
                    testimonial: "I know I can depend on Deno to collaborate with on both large scale projects and smaller casual ones. He is steadfast in his ethical behavior and does not budge from these values according from what I've learned from a professional capacity. In a casual manner he's a friendly person and considerate of others and has a good mentality and outlook on life.",
                    image: "https://i.postimg.cc/vZyhyVkv/Umayar-removebg-preview.png"
                },
                {
                    name: "Uzukhanye Dywili",
                    title: "Intern Developer",
                    testimonial: "Thoughtful, hardworker, caring, smart, and confident are words that best describe Deno. A person who willingly goes an extra mile to get things done.",
                    image: "https://i.postimg.cc/3RrJQnFH/Uzukhanye-removebg-preview.png"
                },
                {
                    name: "John-Bruce Noad",
                    title: "Intern Developer",
                    testimonial: "Deno is a self-confident and determined individual. Once he sets his mind to something, it is near impossible to shift his course.  Deno is not easily bothered by what others think or say about him, and is therefore easy to get along with. When it comes to his work, he is not afraid in the slightest to put his hard-working nature, and his amazing intellect on full display. I have enjoyed working alongside Deno, and can say with absolute confidence that he will be a great asset to any company that affords him the opportunity to present his value.",
                    image: "https://i.postimg.cc/TPMJ0Wqb/John-removebg-preview.png"
                },
                {
                    name: "Luntu Sogeyana",
                    title: "Intern Developer",
                    testimonial: "Deno is a reliable person who is not turn down a fellow coder's cry for help when they need it. His determination to never turn down a challenge, work ethic, and intellect makes him a great asset to have in a team and said team is bound to be successful in whichever task if he is involved in it.",
                    image: "https://i.postimg.cc/vTVm0Dv1/Luntu-removebg-preview.png"
                }
            ],

        downloadURL: 'https://drive.google.com/file/d/1n83D2cESFx-vWTbqv9AiRL_VVO85fibv/view?usp=sharing'
    }
  }
}
</script>


<style scoped>

#welcome {
	width: 70vw;
	margin: 30vw auto;
  }
  
  .welcome {
	text-align: center;
	color: rgb(255, 255, 255);
	text-shadow: 2px 2px 0px #000000;

	margin: 0;
	line-height: 0;
	/*Animation*/
	
	animation: glitch1 2.5s infinite;
  }
  
  .welcome:nth-child(2) {
	color: white;
	animation: glitch2 2.5s infinite;
	text-shadow: 2px 2px 0px #000000;
  }
  
  .welcome:nth-child(3) {
	color: rgb(255, 255, 255);
	animation: glitch3 2.5s infinite;
	text-shadow: 2px 2px 0px #000000;
  }
.roses-about{
	background-image: url('');
	background-repeat: no-repeat;
	background-size: cover;
	object-fit: cover;
	background-position: center;
	border-radius: 20px;
}
  /*Keyframes*/
  
  @keyframes glitch1 {
	0% {
	  transform: none;
	  opacity: 1;
	}
	7% {
	  transform: skew(-0.5deg, -0.9deg);
	  opacity: 0.75;
	}
	10% {
	  transform: none;
	  opacity: 1;
	}
	27% {
	  transform: none;
	  opacity: 1;
	}
	30% {
	  transform: skew(0.8deg, -0.1deg);
	  opacity: 0.75;
	}
	35% {
	  transform: none;
	  opacity: 1;
	}
	52% {
	  transform: none;
	  opacity: 1;
	}
	55% {
	  transform: skew(-1deg, 0.2deg);
	  opacity: 0.75;
	}
	50% {
	  transform: none;
	  opacity: 1;
	}
	72% {
	  transform: none;
	  opacity: 1;
	}
	75% {
	  transform: skew(0.4deg, 1deg);
	  opacity: 0.75;
	}
	80% {
	  transform: none;
	  opacity: 1;
	}
	100% {
	  transform: none;
	  opacity: 1;
	}
  }
  
  @keyframes glitch2 {
	0% {
	  transform: none;
	  opacity: 0.25;
	}
	7% {
	  transform: translate(-2px, -3px);
	  opacity: 0.5;
	}
	10% {
	  transform: none;
	  opacity: 0.25;
	}
	27% {
	  transform: none;
	  opacity: 0.25;
	}
	30% {
	  transform: translate(-5px, -2px);
	  opacity: 0.5;
	}
	35% {
	  transform: none;
	  opacity: 0.25;
	}
	52% {
	  transform: none;
	  opacity: 0.25;
	}
	55% {
	  transform: translate(-5px, -1px);
	  opacity: 0.5;
	}
	50% {
	  transform: none;
	  opacity: 0.25;
	}
	72% {
	  transform: none;
	  opacity: 0.25;
	}
	75% {
	  transform: translate(-2px, -6px);
	  opacity: 0.5;
	}
	80% {
	  transform: none;
	  opacity: 0.25;
	}
	100% {
	  transform: none;
	  opacity: 0.25;
	}
  }
  
  @keyframes glitch3 {
	0% {
	  transform: none;
	  opacity: 0.25;
	}
	7% {
	  transform: translate(2px, 3px);
	  opacity: 0.5;
	}
	10% {
	  transform: none;
	  opacity: 0.25;
	}
	27% {
	  transform: none;
	  opacity: 0.25;
	}
	30% {
	  transform: translate(5px, 2px);
	  opacity: 0.5;
	}
	35% {
	  transform: none;
	  opacity: 0.25;
	}
	52% {
	  transform: none;
	  opacity: 0.25;
	}
	55% {
	  transform: translate(5px, 1px);
	  opacity: 0.5;
	}
	50% {
	  transform: none;
	  opacity: 0.25;
	}
	72% {
	  transform: none;
	  opacity: 0.25;
	}
	75% {
	  transform: translate(2px, 6px);
	  opacity: 0.5;
	}
	80% {
	  transform: none;
	  opacity: 0.25;
	}
	100% {
	  transform: none;
	  opacity: 0.25;
	}
  }
.navbar-nav a::before, .navbar-nav a::after {
	display: inline-block;
	opacity: 0;
	-webkit-transition: -webkit-transform 0.3s, opacity 0.2s;
	-moz-transition: -moz-transform 0.3s, opacity 0.2s;
	transition: transform 0.3s, opacity 0.2s;
}
.navbar-nav a::before {
	margin-right: 10px;
	content: '[';
	-webkit-transform: translateX(20px);
	-moz-transform: translateX(20px);
	transform: translateX(20px);
}
.navbar-nav a::after {
	margin-left: 10px;
	content: ']';
	-webkit-transform: translateX(-20px);
	-moz-transform: translateX(-20px);
	transform: translateX(-20px);
}
.navbar-nav a:hover, .navbar-nav a:hover::before, .navbar-nav a:hover::after, .navbar-nav a:focus::before, .navbar-nav a:focus::after {
	color: rgb(255, 255, 255) !important;
	opacity: 1;
	-webkit-transform: translateX(0px);
	-moz-transform: translateX(0px);
	transform: translateX(0px);
}

.intro, .testimonial-text, .nav-link{
  text-shadow: 2px 2px 0px #000000;
}
.home{
  background-color: black;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
  object-fit: cover;
  min-height: 100vh;
  overflow-x: hidden;
  transition: 0.6s;
}





img {
	height: 50vh;
	object-fit: cover;
}
.bg-image{
  background-image: url('https://i.postimg.cc/qRpLTNQW/photo-1559456964-a49e2f0cf0d3.jpg');
  background-repeat: no-repeat;
  background-size: cover;
  object-fit: cover;
  height: 450px;
}

.resume{
	background-image: url('https://i.postimg.cc/zX6bjrRC/photo-1629694242273-71ac9adbf6e1.jpg');
	background-repeat: no-repeat;
	background-size: cover;
	object-fit: cover;	
	background-position: center;

}
#projects{
	background-image: url('https://i.postimg.cc/fySq0s9H/2-xea1fin.jpg');
	background-repeat: no-repeat;
	background-size: cover;
	object-fit: cover;	
	background-position: bottom;


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



.container-fluid-mouse {
	width: 100%;
	display: flex;
	align-items: center;
	justify-content: center;
}

.field {
	display: flex;
	align-items: center;
	justify-content: space-around;
	width: 300px;
}

.mouse {
	width: 35px;
	height: 60px;
	border: 3px solid #ffffff;
	border-radius: 60px;
	position: relative;
	&::before {
		content: '';
		width: 12px;
		height: 12px;
		position: absolute;
		top: 10px;
		left: 50%;
		transform: translateX(-50%);
		background-color: #ffffff;
		border-radius: 50%;
		opacity: 1;
		animation: wheel 2s infinite;
		-webkit-animation: wheel 2s infinite;
	}
}

@keyframes wheel {
	to {
		opacity: 0;
		top: 50px;
	}
}

@-webkit-keyframes wheel {
	to {
		opacity: 0;
		top: 50px;
	}
}



.progress-title{
	color: #fff;
	text-transform: uppercase;
	letter-spacing: 2px;
	margin: 0 0 30px;
	}
	
	.progress{
	height: 10px;
	background: #000;
	border-radius: 0;
	box-shadow: none;
	margin-bottom: 40px;
	overflow: visible;
	position: relative;
	}
	
	.progress .progress-bar{
	background: #fff;
	border-radius: 0;
	position: relative;
	-webkit-animation: animate-positive 2s;
	animation: animate-positive 2s;
	}
	
	.progress .progress-bar:before{
	content: "";
	width: 100%;
	border-top: 10px double #f95738;
	border-right: 25px solid #000;
	position: absolute;
	top: 0;
	left: 0;
	}
	
	.progress .progress-value{
	font-size: 18px;
	font-weight: 700;
	color: #000;
	position: absolute;
	top: -32px;
	right: -5px;
	}
	
	.progress.dark-green .progress-bar:before{
	border-top-color: #68a063;
	}
	.progress.light-blue .progress-bar:before{
	border-top-color: #00758f;
	}
	.progress.purple .progress-bar:before{
	border-top-color: purple;
	}
	.progress.orange .progress-bar:before{
	border-top-color: orangered;
	}
	.progress.w-blue .progress-bar:before{
	border-top-color: #21759b;
	}
	.progress.r-blue .progress-bar:before{
	border-top-color: #61dbfb;
	}
	.progress.yellow .progress-bar:before{
	border-top-color: #ecb82d;
	}
	.progress.dark-yellow .progress-bar:before{
	border-top-color: #ffde57;
	}
	
	.progress.green .progress-bar:before{
	border-top-color: #42b883;
	}
	
	.progress.blue .progress-bar:before{
	border-top-color: #165692;
	}
	
	@-webkit-keyframes animate-positive{
	0% { width: 0; }
	}
	
	@keyframes animate-positive{
	0% { width: 0; }
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
		background-color: #ffffff;
		bottom: 0;
		left: 50%;
		margin-left: -30px;
	}
	.section-title h4:after {
		position: absolute;
		background-color: #ffffff;
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
		background-color: #ffffff;
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
		border: 2px solid #000000;
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
		background-color: #ffffff;
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
		color: #000000;
	}
	
	.card-body::after {
		height: 0;
		left: 0;
		bottom: 0;
		width: 100%;
		border-top: 2.5px solid rgb(0, 0, 0) !important; 
		-webkit-transition: all 0.35s;
		  -moz-transition: all 0.35s;
		-o-transition: all 0.35s;
		  transition: all 0.35s;
		  
	  }
	  
	  .card-body::before,
	  .card-body::after {
		background: rgb(255, 255, 255);
		content: '';
		position: absolute;
		z-index: -1;
	
	  }
	  
	  .card:hover {
		color: #000000;
		opacity: 0.5;
		transition: 0.5s
	  }
	  
	  .card:hover .card-body:after {
		height: 100%;
		color: #000000;
	  }
	  
	  .card-body {  
		position: relative;
		z-index: 1;
		-webkit-transition: all 0.35s ease;
		  -moz-transition: all 0.35s ease;
		-o-transition: all 0.35s ease;
		  transition: all 0.35s ease;
	  }
	  .testimonials{
        background-image: url("https://i.postimg.cc/132sNm2F/Existence-of-black-roses-on-Thursd.jpg");
		background-repeat: no-repeat;
		background-size: cover;
		object-fit: cover;
	}

</style>
