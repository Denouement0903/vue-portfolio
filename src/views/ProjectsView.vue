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
                                  <a :href=project.netlify class="btn btn-primary m-3">Netlify</a>
                                  <a :href=project.github class="btn btn-primary m-3">Github</a>
                                </div>
                          </div>
                    </div>
            </div>
        </div>
    </div>
</template>
<script>
// create a backend for projects
export default {
    name: 'projects',
    data(){
        return{
            projectsArray: [
                {
                    id: 1,
                    name: "Manga Site",
                    description: "A E-commerce project using VUEJS and NODE JS and API Functionality",
                    image: "https://i.postimg.cc/yxs7RY5z/Screenshot-2023-03-28-161820.png",
                    netlify: "https://mangako-deno-rautenbach.netlify.app/",
                    github: "https://github.com/Simp4Hitagi/Capstone-Mangako"
                },
                {
                    id: 2,
                    name: "Figures Site",
                    description: "A collaborative E-commerce project using VUEJS and NODE JS",
                    image: "https://i.postimg.cc/DwMsPtnN/Screenshot-2023-03-28-162401.png",
                    netlify: "",
                    github: "https://github.com/Simp4Hitagi/Otaku"
                },
                {
                    id: 3,
                    name: "Calculator",
                    description: "A basic calculator app built using HTML, CSS, Bootstrap and Javascript",
                    image: "https://i.postimg.cc/fbN8V6q4/calculator.png",
                    netlify: "https://deno-calculator.netlify.app",
                    github: "https://github.com/Simp4Hitagi/My_Calculator"
                },
                {
                    id: 4,
                    name: "Vue Portfolio",
                    description: "A updated of the current portfolio project using Vue, JS, HTML and CSS ",
                    image: "https://i.postimg.cc/gcTMrB6g/Screenshot-2023-03-28-162020.png",
                    netlify: "https://deno-vue-portfolio.netlify.app/",
                    github: "https://github.com/Simp4Hitagi/vue-portfolio"
                },
                {
                    id: 5,
                    name: "Point of Sale System",
                    description: "E-Commerce ste with a CRUD system primarily built using JS, HTML and CSS",
                    image: "https://i.postimg.cc/cH96MZhK/pos-system.png",
                    netlify: "https://deno-pos.netlify.app/index.html",
                    github: "https://github.com/Simp4Hitagi/PointOfSale_System"
                },
                {
                    id: 6,
                    name: "Tribute Page",
                    description: "A basic page to showcase cool art using mainly HTML and CSS",
                    image: "https://i.postimg.cc/3Jk3TwkS/tribute-page.png",
                    netlify: "https://deno-tributepage.netlify.app",
                    github: "https://github.com/Simp4Hitagi/excercise"
                },
                {
                    id: 7,
                    name: "Portfolio",
                    description: "My first Portfolio project using HTML, CSS and Bootstrap",
                    image: "https://i.postimg.cc/cJ2qxRPr/portfolio.png",
                    netlify: "https://deno-portfolio1.netlify.app",
                    github: "https://github.com/Simp4Hitagi/Final_Portfolio_Project"
                },


                
                {
                    id: 8,
                    name: "Animation Site",
                    description: "A animation project using HTML and CSS as basic practice",
                    image: "https://i.postimg.cc/YqgRP8Bp/Screenshot-2023-01-14-133534.png",
                    netlify: "animation-deno.netlify.app",
                    github: "https://github.com/Simp4Hitagi/animation"
                },

            ]
        }
    }
}
</script>
<style scoped>
    
</style>