<template>
  <section class="projects" id="Projects">
    <h2>My Projects</h2>
    <div class="row ">
      
      <div class="col-sm-6 mb-3 mb-sm-0">
        <div class="card bg-dark h-100">
          <div class="d-flex">
            <div class="card-body">           
                <img src="/assets/img/TopUp-in2.png" style="width: 400px;" alt="TopUp.in" class="d-flex justify-content-center align-items-center">
            </div>
            <div class="card-body ">           
                <h5 class="card-title">TopUp.in</h5>
                <p class="card-text d-flex">TopUp.in is a SiPPOB website</p>
                <a href="https://github.com/Syamsoelll/SiPPOB-UAS" class="btn btn-primary d-flex justify-content-center align-items-center" target="_blank">
                  Go to the project
                </a>
            </div>
          </div>
        </div>
      </div>
      <div class="col-sm-6">
        <div class="card bg-dark h-100">
          <div class="d-flex">
          <div class="card-body">           
                <img src="/assets/img/GerbangLogika.png" style="width: 400px;" alt="TopUp.in" class="d-flex justify-content-center align-items-center">
          </div>
          <div class="card-body">
            <h5 class="card-title">Simulator Gerbang Logika</h5>
            <p class="card-text">Logic Gate Simulator is a website for simulating logic gates</p>
            <a href="https://github.com/Syamsoelll/Simulator-Gerbang-Logika" class="btn btn-primary d-flex justify-content-center align-items-center" target="_blank">
              Go to the project
            </a>
          </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'ProjectsSection'
}
</script>

<style scoped>
.projects {
  padding: 50px 200px;
  background-color: #222831;
  color: white;
}
</style>
