<template>
      <div class="container-fluid">
        <div class="row bg-dark rounded-2">
          <div class="col-md-6">
               <h3 class="progress-title">HTML5 == 95%</h3>
               <div class="progress orange">
                   <div class="progress-bar" style="width:95%;">
                       <div class="progress-value">95%</div>
                   </div>
               </div>
               <h3 class="progress-title">CSS3 == 89%</h3>
               <div class="progress blue">
                   <div class="progress-bar" style="width:89%;">
                       <div class="progress-value">89%</div>
                   </div>
               </div>
        
               <h3 class="progress-title">JS == 72%</h3>
               <div class="progress yellow">
                   <div class="progress-bar" style="width:72%;">
                       <div class="progress-value">72%</div>
                   </div>
               </div>
               <h3 class="progress-title">VUEJS == 79%</h3>
               <div class="progress green">
                   <div class="progress-bar" style="width:79%;">
                       <div class="progress-value">79%</div>
                   </div>
               </div>
               <h3 class="progress-title">MySQL == 91%</h3>
               <div class="progress light-blue">
                   <div class="progress-bar" style="width:91%;">
                       <div class="progress-value">91%</div>
                   </div>
               </div>
               <h3 class="progress-title">BOOTSTRAP == 93%</h3>
               <div class="progress purple">
                   <div class="progress-bar" style="width:93%;">
                       <div class="progress-value">93%</div>
                   </div>
               </div>
               <h3 class="progress-title">NODEJS == 69%</h3>
               <div class="progress dark-green">
                   <div class="progress-bar" style="width:69%;">
                       <div class="progress-value">69%</div>
                   </div>
               </div>
               <h3 class="progress-title">PYTHON == 57%</h3>
               <div class="progress dark-yellow">
                   <div class="progress-bar" style="width:57%;">
                       <div class="progress-value">57%</div>
                   </div>
               </div>
           </div>
           <div class="col-md-6 my-5">
            <h2 class="text-center display-1">SKILLS</h2>
            <img class="w-75 rounded-5 mx-auto my-5 d-block" src="https://i.postimg.cc/x1whqSPr/jay-versace-typing.gif" alt="">
            <h4 class="display-4 text-center">Fun Stuff</h4>
           </div>
        </div>
        </div>
</template>
<script>
export default {
  name: 'resume'
};
</script>
<style scoped>
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
</style>

<section class="experience pt-100 pb-100" id="experience">
  <div class="container">
    <div class="row">
      <div class="col-xl-8 mx-auto text-center">
        <div class="section-title">
          <h4>bootstrap 5 timeline</h4>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit</p>
        </div>
      </div>
    </div>
    <div class="row">
             <div class="col-xl-12">
                <ul class="timeline-list">
                   <!-- Single Experience -->
                   <li>
                      <div class="timeline_content">
                         <span>2008</span>
                         <h4>Intern Developer span</h4>
                         <p>We gather your business and products information. We then determine the direction of the project and understand your goals and we combine your ideas with ours for an amazing website.</p>
                      </div>
                   </li>
                   <!-- Single Experience -->
                   <li>
                      <div class="timeline_content">
                      <span>2007-2012</span>
                         <h4>Junior Developer</h4>
                         <p>We gather your business and products information. We then determine the direction of the project and understand your goals and we combine your ideas with ours for an amazing website.</p>
                      </div>
                   </li>
                   <!-- Single Experience -->
                   <li>
                      <div class="timeline_content">
                      <span>2012-2015</span>
                         <h4>Senior Developer</h4>
                         <p>We gather your business and products information. We then determine the direction of the project and understand your goals and we combine your ideas with ours for an amazing website.</p>
                      </div>
                   </li>
                   <!-- Single Experience -->
                   <li>
                      <div class="timeline_content">
                      <span>2015-2018</span>
                         <h4>Project Manager</h4>
                         <p>We gather your business and products information. We then determine the direction of the project and understand your goals and we combine your ideas with ours for an amazing website.</p>
                      </div>
                   </li>
                </ul>
             </div>
          </div>
  </div>
  </section>