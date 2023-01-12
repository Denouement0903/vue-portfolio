<template>
    <div>
        <h1 class="display-1 fw-bold">Resume</h1>
        <section class="skills">
            <h1 class="display-4">Skills</h1>
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