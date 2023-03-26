<template>
  <div class="resume">
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
          <h2 class="text-center display-1 text-light">SKILLS</h2>
          <img class="w-75 rounded-5 mx-auto my-5 d-block" src="https://i.postimg.cc/x1whqSPr/jay-versace-typing.gif" alt="">
          <h4 class="display-5 text-center text-light">Download my CV</h4>
          <button type="button" class="btn btn-danger rounded-2 mx-auto d-block my-5">
            <a target="_blank" class="text-light" :href="downloadURL" download>Download</a>
            </button>
         </div>
      </div>
      </div>
      <div class="work-education bg-dark opacity-75 my-5 rounded-2">
        <section class="experience pt-100 pb-100" id="experience">
  <div class="container-fluid">
    <div class="row">
      <div class="col-xl-8 mx-auto text-center">
        <div class="section-title">
          <h4 class="text-light">Education and Experience</h4>
          <h5>Let's take a trip down memory lane...</h5>
        </div>
      </div>
    </div>
    <div class="row">
             <div class="col-xl-12">
                <ul class="timeline-list">
                   <!-- Single Experience -->
                   <li>
                      <div class="timeline_content">
                         <span>15 Jan 2017</span>
                         <h4>Start of Highschool</h4>
                         <p>I started grade 8 at <span class="font-weight-bold text-danger">Villiersdorp Secondary School.</span> I matriculated with a Bachelors pass. 
                          My Subjects Included:
                          <em>Afrikaans HL,
                          English FAL,
                          Maths,
                          Life Sciences,
                          Geography,
                          Computer Applications Technology,
                          Life Orientation</em>
                        </p>
                        
                      </div>
                   </li>
                   
                        <li>
                      <div class="timeline_content">
                      <span>Dec 2021</span>
                         <h4>End Of Highschool</h4>
                         <p>I was Best in Afrikaans and English, 2nd best in Math, Geography and Computer Applications Technology, 3rd best in Life Science and achieved a distinction in English FAL in 2021 for Matric.</p>
                      </div>
                   </li>
                   
                   <li>
                      <div class="timeline_content">
                      <span>11 Feb 2022</span>
                         <h4>Start of Job</h4>
                         <p>I acquired my first hands-on job experience at a company called <span class="font-weight-bold text-danger">Tech Nasty.</span> During my time at Tech Nasty my designation was as an assistant in Information Technology and Computer repair. This involved troubleshooting of hardware and software issues and repair as well as selling of technology and services. My key responsibilities included shop management and assistance.</p>
                      </div>
                   </li>
                   
                   <li>
                      <div class="timeline_content">
                      <span>15 Mar 2021</span>
                         <h4>End of Job</h4>
                         <p>My reason for leaving was the indefinite closure of Tech Nasty due to the restrictions brought forth by the Covid-19 pandemic at the time. Also another contributing factor was that I was self-studying and it was in the time of me having remote classes as well as working at the aforementioned company simultaneously.</p>
                      </div>
                   </li>
                </ul>
             </div>
          </div>
  </div>
  </section>
      </div>
  </div>
</template>
<script>
export default {
  name: 'resume',
  data() {
    return {
        downloadURL: 'https://drive.google.com/file/d/1gtIqSWnem4Vew2q4iLa-NiaFjo9QfoOr/view?usp=sharing'
    }
  }
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
	background-color: #ff3636;
	bottom: 0;
	left: 50%;
	margin-left: -30px;
}
.section-title h4:after {
	position: absolute;
	background-color: #ff3636;
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
	background-color: #ff3636;
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
	border: 2px solid #ff3636;
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
	background-color: #ff3636;
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
	color: #ff3636;
}


</style>