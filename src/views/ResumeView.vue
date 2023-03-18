<template>
    <div>
        <h1 class="display-1 fw-bold animate__animated animate__fadeInDown">Resume</h1>
        <section class="skills">
            <h1 class="display-4 animate__animated animate__fadeInDown">Skills</h1>
            <h2 class="text-primary">HTML</h2>
            <div class="progress m-3" role="progressbar" aria-label="Default striped example" aria-valuenow="10" aria-valuemin="0" aria-valuemax="100">
                <div class="progress-bar progress-bar-striped progress-bar-animated" style="width: 93%">93%</div>
              </div>
              <h2 class="text-success">Vue</h2>
              <div class="progress m-3" role="progressbar" aria-label="Success striped example" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">
                <div class="progress-bar progress-bar-striped progress-bar-animated bg-success" style="width: 53%">53%</div>
              </div>
              <h2 class="text-info">Bootstrap</h2>
              <div class="progress m-3" role="progressbar" aria-label="Info striped example" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100">
                <div class="progress-bar progress-bar-striped progress-bar-animated bg-info" style="width: 87%">87%</div>
              </div>
              <h2 class="text-warning">JavaScript</h2>
              <div class="progress m-3" role="progressbar" aria-label="Warning striped example" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100">
                <div class="progress-bar progress-bar-striped progress-bar-animated bg-warning" style="width: 69%">69%</div>
              </div>
              <h2 class="text-danger">CSS</h2>
              <div class="progress m-3" role="progressbar" aria-label="Danger striped example" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100">
                <div class="progress-bar progress-bar-striped progress-bar-animated bg-danger" style="width: 83%">83%</div>
              </div>
        </section>
        <section class="work&education">          
          <div class="accordion" id="accordionExample">
            <div class="accordion-item">
              <h2 class="accordion-header" id="headingOne">
                <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">

                  <h3 class="mx-1 my-2 shadow">Education</h3>          
                </button>
              </h2>
              <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne" data-bs-parent="#accordionExample">
                <div class="accordion-body">
                  <h4 class="shadow">15 Jan 2017</h4>
                  <h5>Start of highschool</h5>
                  <p class="lead shadow text-black">I started grade 8 at Villiersdorp Secondary School.</p>
                  <h4 class="shadow">Dec 2021</h4>
                  <h5>End of highschool</h5>
                  <p class="lead shadow text-black">I matriculated with a Bachelors pass.</p>
                  <h6>Subjects</h6>
                  <ul>
                    <li class="list-unstyled">Afrikaans HL</li>
                    <li class="list-unstyled">English FAL</li>
                    <li class="list-unstyled">Maths</li>
                    <li class="list-unstyled">Life Sciences</li>
                    <li class="list-unstyled">Geography</li>
                    <li class="list-unstyled">Computer Applications Technology</li>
                    <li class="list-unstyled">Life Orientation</li>
                  </ul>
                  <h6>Achievements</h6>
                  <p class="lead shadow text-black">I was Best in Afrikaans and English, 2nd best in Math, Geography and Computer Applications Technology, 3rd best in Life Science and achieved a distinction in English FAL in 2021 for Matric.</p>
                </div>
              </div>
            </div>
            <div class="accordion-item">
              <h2 class="accordion-header" id="headingTwo">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                  <h3 class="mx-1 my-2 shadow">Experience</h3>
                </button>
              </h2>
              <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#accordionExample">
                <div class="accordion-body">
                  <h4 class="shadow">11 Feb 2020</h4>
                  <h5>Start of Job at <strong>Tech Nasty</strong></h5>
                  <p class="lead shadow text-black">During my time at Tech Nasty my designation was as an assistant in Information Technology and Computer repair.  This involved troubleshooting of hardware and software issues and repair as well as selling of technology and services. My key responsibilities included shop management and assistance.</p>
                  <h4 class="shadow">15 Mar 2021</h4>
                  <h6>End of Job</h6>
                  <p class="lead shadow text-black">My reason for leaving was the indefinite closure of Tech Nasty.</p>
                </div>
              </div>
            </div>
          </div>         
        </section>
    </div>
</template>
<script>
export default {
    name: 'resume'
    
}
</script>
<style scoped>
    
</style>