<template>
  <div class="home">
    <div class="container-fluid">
      <div class="row">
        <div class="col-7 my-auto">
          <div class="typewriter my-auto">
          <h1 class="display-2">//  Hello There</h1>
          </div>
          <div class="socials my-5">
            <ul class="list-unstyled">
              <li class="fw-bold">
                <!-- Github -->
                <a href="https://github.com/Simp4Hitagi" class="tw-ic" target="_blank">
                    <img loading="lazy" width="51" height="51" src="https://img.icons8.com/glyph-neue/64/github.png">
                </a>
                Github
              </li>
              <li class="fw-bold">
                <!--Linkedin -->
                <a href="https://www.linkedin.com/in/deno-rautenbach-b1698018a" class="li-ic" target="_blank">
                    <img loading="lazy" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAYAAABXAvmHAAAACXBIWXMAAAsTAAALEwEAmpwYAAADOElEQVR4nO1ZS2tTQRQ++Fq4tAq+xR+h2L24FqEoundZosXMGCtxZbvWlrT0HyhawcfGhdgYTWm1JGcaXHRh26hgm742SWzqyJmbhKTm5s7NnXsTIR8cmMyEyffNnDlz5gSgiy668I6+J3uBp3uBYQSYeAYM54GLNeDid9nWgKMoj0UgnLkAUbkH2o57eAo4DgMTWeBCurRl4DgE4dTJ4Inf/XIEOI4Dw2ILxOuNYRGYiMHtr4eDIc/EdeCY80z8XyGrEMZr/hG/ObsfuJgwTpzvNhxTv2UU0dmDwPGN/+RFZTdeq980t/IBkufVnXgLUXHAu4BA3EbY7ISIeSV/w3byO58lhBKWUdu/nbjaIvlMD3BcsSN/ZQLlj42i/LlZVG3/RGCutRBLcd5u0lBCka8gu16wdsI/Vxp1R55ux2aXVCghv28UqgKo7a8ApMvutJvVH246YdmFyH1o9S+Pp30+B4JcaUiPPCVZKk9xmDCwQywqbpRVSaPz6qd7HScLfZLQ/6HeqK/ZGEtLGJiREPpY7ktYn6lfV0RYnHcWQOmu00T9cbkb1Gc/NiXPRKfl6Pus/JbLy+L2jlxeL8ixeFaefTCtv4NMcI0dEM9NC7j4aE5u5rdlI2zlS/LSSEpPBMOnGgJQmBZAJJthK19SO6ThTmkdATnTAnQQm8paZ6J5JFrROQNF0wLI58OTC/L4/aQy9mJB9dViMZfXuEuw0BYBRNhaXbRsYEb11aK088eKTp4F+OBCxwaTZfJVIvLoYNJ+Dk8u5MMhbkhM93vc9SE2H0aNCWA6YdSXi8zYDjBnAVR06lgBeE4vmWNiqfME4KJ+NY9S104TwPChHnmdB03gArAAkbkT4ApUEegUAQwfg2vcEodsH/Uqp4/XG/U5jenOwevIr7ZeN6VapVNE8t3m+8ATqFbZNvI4Ap5B71CGk20Q8Aqi7/aBEVChlQquQZFn4qW54m5tkbdZZDLpNlFTK98IVKu0i07eVv2X9wOrLSLTo8p9dMF4X/GCivMUtgMH3Y6UdjjlTo1XfEmlB65vWD9ASRYVnahuQzk7PTzoZadqmpSSUFukymNMZZUd8TdrF13Af4+/0+/tR7SO3T4AAAAASUVORK5CYII=">
                </a>
                Work
              </li>

                <li class="fw-bold">
                  <!--Instagram-->
                  <a href="https://www.instagram.com/denonouement09/" class="ins-ic" target="_blank">
                      <img loading="lazy" src="data:image/png;base64,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">
                  </a>
                 Lifestyle
                </li>
                <li>
                  <a href="#preview" >
                    <div class="container-scroll">
              <div class="field">
                
                <div class="scroll"></div>
                
              </div>
            </div>

                  </a>

          </li>
            </ul>
          </div>
        </div>      
        <div class="col-5 mx-auto">
          <img src="https://i.postimg.cc/MTQDqhtg/IMG-3354-3-removebg-preview.png" class="lazy" alt="">
        </div>
        <h2 class="display-1 font-weight-bold" id="preview">Preview My Projects</h2>
        <div id="carouselExampleAutoplaying" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <iframe src="https://mangako-nipon.web.app/" height="1000" title="description" class="mx-auto"></iframe>
    </div>
    <div class="carousel-item">
      <iframe src="https://deno-calculator.netlify.app/" height="1000" title="description"></iframe>
    </div>
    <div class="carousel-item">
      <iframe src="https://deno-pos.netlify.app/index.html" height="1000" title="description"></iframe>
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleAutoplaying" data-bs-slide="prev">
    <span class="carousel-control-prev-icon bg-dark rounded-3" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleAutoplaying" data-bs-slide="next">
    <span class="carousel-control-next-icon bg-dark rounded-3" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
</div>
    </div>
  </div>
  <br/>
  <br/>
</template>
<script>
export default {
  name: 'HomeView'
}
</script>
<style scoped>
.container-scroll {
	width: 100%;
	height: 100%;
	display: flex;
	align-items: center;
	justify-content: center;
  margin-left: 15rem;
  margin-top: 5rem;
}

.field {
	display: flex;
	align-items: center;
	justify-content: space-around;
	width: 300px;
}
.scroll {
	width: 60px;
	height: 60px;
	border: 4px solid black;
	border-radius: 50%;
	position: relative;
	animation: down 1.5s infinite;
	-webkit-animation: down 1.5s infinite;
	&::before {
		content: '';
		position: absolute;
		top: 15px;
		left: 18px;
		width: 18px;
		height: 18px;
		border-left: 4px solid black;
  	border-bottom: 4px solid black;
		transform: rotate(-45deg);
	}
}

@keyframes down {
	0% {
		transform: translate(0);
	}
	20% {
		transform: translateY(15px);
	}
	40% {
		transform: translate(0);
	}
}

@-webkit-keyframes down {
	0% {
		transform: translate(0);
	}
	20% {
		transform: translateY(15px);
	}
	40% {
		transform: translate(0);
	}
}

@keyframes scroll {
	0% {
		height: 40px;
	}
	30% {
		height: 70px;
	}
	60% {
		height: 40px;
	}
}

@-webkit-keyframes scroll {
	0% {
		height: 40px;
	}
	30% {
		height: 70px;
	}
	60% {
		height: 40px;
	}
}





.typewriter h1 {
  overflow: hidden; /* Ensures the content is not revealed until the animation */
  border-right: .15em solid gold; /* The typwriter cursor */
  white-space: nowrap; /* Keeps the content on a single line */
  margin: 0 auto; /* Gives that scrolling effect as the typing happens */
  letter-spacing: .15em; /* Adjust as needed */
  animation: 
    typing 3.5s steps(30, end),
    blink-caret .5s step-end infinite;
}

/* The typing effect */
@keyframes typing {
  from { width: 0 }
  to { width: 100% }
}

/* The typewriter cursor effect */
@keyframes blink-caret {
  from, to { border-color: transparent }
  50% { border-color: orangered }
}

iframe {
    width: 1000px;
    height: 500px;
    margin: 0 auto;
    display:block;
}
</style>
