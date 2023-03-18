<template>
    <div>
      <nav class="navbar navbar-expand-lg">
        <div class="container-fluid">
          <a class="navbar-brand" href="/"><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEAAAABACAYAAACqaXHeAAAACXBIWXMAAAsTAAALEwEAmpwYAAAC/ElEQVR4nO2ZTYiNURjHf2OkGDMLCqVkRGF8dX2NjyIjC5GkKBuRhhUrKSmyYoXSlIXNpORjo2uhmMZMQ4kVSSYbqykfISXN3Dt06ty63d5z5pzznvth3udXZ3XPec7z/N/z8ZzngiAIgiAIgiAIglBX+oC/Fe0TGWEG8CdBgNtkhN0Jwat2koxw1SBABxnhXULw34ApZID5hq//kP+MrcCTgHHHDAKcMfQfBPbSYIH3aafHAsbfMQjQaeg/pn9/DnRRRzbrL17utK8Aao9/Tgj+NzBtAgFKbQjYQQ3pBPKGr+YrwDqDnX7LmEoByoXYThXZaAk8VIBzBjuXAgQoNbUqNxCRVcA9YHyCiUME6DfY2ZVCgHIh1qcJfIVH4Kp90BmdKy2G9LcAtFrGqf3+1tGnkhBrfQLvAHqBouMEv4CLlkPLxB6DvdcOY6cCp4Efjj6O6+2bsxldrgMveBhV/ecSxnWD3WseNmZrOwVPIdaUG1kE3PQwotorYBPpeG+wfSDAVk7nBa7+F/X2Xopn4CPAEaApZfALLHPMC7TZpH0b8YingGPHUb3U2ojDccM8wxFst+gzKemATWpM1OFpFZ6ldw1z3Yo4xxLgUQwB8kB7RMeaga+GuY5GfmX2OlzjuCwTlZtfBmZGyihN8yyOYH86cFZfz05boOBxaKgi5aGUDp63HLBpOah99DoE2wOuwZf6S4YwaLB5P0Xg6l4fCL0GSyzzTISKuv8c3GnVN0qSvVP4MytGIpQ2Ff6u95xLKrzPYseapiakwt3AF8/Ac/V+DN0wjP2pbwcX1GPoTTUfQ5WsjPgcHjaMe4w7NXsOV7JaCxEqwELLOHUzuFLzgkisktgJi9PbcKduJbGkomjeQ4AHBsdH9X+DrtS9KFrJFv1esAnQrP/pSRLgBX6Ul8V30kB0Ac8s28a0/K94zjPQaIG7cMEiQEP9y1MthiwJiiprTWraLOmvqu5OevZbln8PGaDHIsBhMsBHiwCqOCoIgiAIgiAIgiBQY/4BjkjADnfPreoAAAAASUVORK5CYII="></a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
            <div class="navbar-nav">
              <router-link style="text-decoration:none" class="nav-link active" aria-current="page"  to="/">Home</router-link>
              <router-link style="text-decoration:none" class="nav-link" to="/about">About</router-link>
              <router-link style="text-decoration:none" class="nav-link" to="/resume">Resume</router-link>
              <router-link style="text-decoration:none" class="nav-link" to="/projects">Projects</router-link>
              <router-link style="text-decoration:none" class="nav-link" to="/testimonials">Testimonials</router-link>
              <router-link style="text-decoration:none" class="nav-link" to="/contact">Contact</router-link>
            </div>
          </div>
        </div>
      </nav>
    </div>
</template>
<script>
export default {
    name: 'navbar'
}
</script>
<style scoped>
router-link:hover {
color: aqua;
}
</style>