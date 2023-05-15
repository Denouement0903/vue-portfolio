<template>
    <div>
        <h1 class="display-1 fw-bold animate__animated animate__fadeInDown">Projects</h1> 
        <div class="container">
            <div class="row">
                    <div class="col" v-for="project in projectsArray" :key="project">
                        <div class="card mx-auto my-3 border border-dark border-4 " style="width: 18rem;">
                                <img :src=project.image class="card-img-top" alt="..." style="height: 13rem;">
                                <div class="card-body border border-warning border-4">
                                  <h5 class="card-title">{{project.name}}</h5>
                                  <p class="card-text">{{project.description}}</p>
                                  <a :href=project.hosted class="btn btn-primary m-3"  target="_blank">Hosted</a>
                                  <a :href=project.github class="btn btn-primary m-3"  target="_blank">Github</a>
                                </div>
                          </div>
                    </div>
            </div>
        </div>
        <!-- python terminal -->
        <!-- <div ref="terminalContainer"></div> -->
    </div>
</template>
<script>
// create a backend for projects
import { Terminal } from 'xterm';
import { FitAddon } from 'xterm-addon-fit';
export default {
    name: 'projects',
    mounted() {
        const terminalContainer = this.$refs.terminalContainer;
        const term = new Terminal();
        const fitAddon = new FitAddon();
    
        term.loadAddon(fitAddon);
        term.open(terminalContainer);
        fitAddon.fit();
    
        // You can now use `term` to interact with the terminal
        term.write('Hello, world!\r\n');
      },
    data(){
        return{
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
                    name: "Tribute Page",
                    description: "A basic page to showcase cool art using mainly HTML and CSS",
                    image: "https://i.postimg.cc/3Jk3TwkS/tribute-page.png",
                    hosted: "https://deno-tributepage.netlify.app",
                    github: "https://github.com/Simp4Hitagi/excercise"
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

            ]
        }
    }
}
</script>
<style scoped>
    
.card-body::after {
  height: 0;
  left: 0;
  bottom: 0;
  width: 100%;
  border-top: 2.5px solid gold !important; 
  -webkit-transition: all 0.35s;
	-moz-transition: all 0.35s;
  -o-transition: all 0.35s;
	transition: all 0.35s;
}

.card-body::before,
.card-body::after {
  background: lemonchiffon;
  content: '';
  position: absolute;
  z-index: -1;
}

.card:hover {
  color: #000;
}

.card:hover .card-body:after {
  height: 100%;
  color: #fff;
}

.card-body {  
  position: relative;
  z-index: 0;
  -webkit-transition: all 0.35s ease;
	-moz-transition: all 0.35s ease;
  -o-transition: all 0.35s ease;
	transition: all 0.35s ease;
}

</style>