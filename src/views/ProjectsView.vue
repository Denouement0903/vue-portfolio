<template>
    <div>
        <h1 class="display-1 fw-bold animate__animated animate__fadeInDown">Projects</h1> 
        <div class="container">
            <div class="row">
                    <div class="col" v-for="project in projectsArray" :key="project">
                        <div class="card mx-auto my-3" style="width: 18rem;">
                                <img :src=project.image class="card-img-top" alt="...">
                                <div class="card-body">
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
    <Footer/>
</template>
<script>
import Footer from '@/components/Footer.vue'
export default {
    name: 'projects',
    components: {
        Footer
    },
    data(){
        return{
            projectsArray: [
                {
                    id: 1,
                    name: "Calculator",
                    description: "A basic calculator app built using HTML, CSS, Bootstrap and Javascript",
                    image: "https://i.postimg.cc/fbN8V6q4/calculator.png",
                    netlify: "https://deno-calculator.netlify.app",
                    github: "https://github.com/Simp4Hitagi/My_Calculator"
                },
                {
                    id: 2,
                    name: "Portfolio",
                    description: "Portfolio project using HTML, CSS and Bootstrap",
                    image: "https://i.postimg.cc/cJ2qxRPr/portfolio.png",
                    netlify: "https://deno-portfolio1.netlify.app",
                    github: "https://github.com/Simp4Hitagi/Final_Portfolio_Project"
                },
                {
                    id: 3,
                    name: "Point of Sale System",
                    description: "E-Commerce ste with a CRUD system primarily built using JS, HTML and CSS",
                    image: "https://i.postimg.cc/cH96MZhK/pos-system.png",
                    netlify: "https://deno-pos.netlify.app/index.html",
                    github: "https://github.com/Simp4Hitagi/PointOfSale_System"
                },
                {
                    id: 4,
                    name: "Tribute Page",
                    description: "A basic page to showcase cool art using mainly HTML and CSS",
                    image: "https://i.postimg.cc/3Jk3TwkS/tribute-page.png",
                    netlify: "https://deno-tributepage.netlify.app",
                    github: "https://github.com/Simp4Hitagi/excercise"
                },
                {
                    id: 5,
                    name: "Vue Portfolio",
                    description: "A portfolio project using Vue, JS, HTML and CSS",
                    image: "https://i.postimg.cc/XYLVSZGX/vue-portfolio.png",
                    netlify: "deno-vue-portfolio.netlify.app",
                    github: "https://github.com/Simp4Hitagi/vue-portfolio"
                }
            ]
        }
    }
}
</script>
<style scoped>
    
</style>