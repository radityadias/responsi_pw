<template>
    <nav class="navbar bg-body-tertiary">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">
          <span class="brand-name">RADIT</span>
        </a>
        <nav class="navbar navbar-expand-lg bg-body-tertiary">
          <div class="container-fluid justify-content-center"> 
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse justify-content-center" id="navbarNavAltMarkup">
              <div class="navbar-nav">
                <a class="nav-link active text-dark" aria-current="page" href="#home">HOME</a>
                <a class="nav-link text-dark" href="#projects">PROJECT</a>
                <a class="nav-link text-dark" href="#hobby">HOBBY</a>
                <a class="nav-link text-dark" href="#hero">ABOUT</a>
              </div>
            </div>
          </div>
        </nav>
      </div>
    </nav>
</template>

<script>
    export default{
        name: 'myHeader'
    }
</script>

<style scoped>

.navbar .nav-link,
.navbar .navbar-brand {
  color: rgb(67, 71, 120) !important;
  font-family: 'Poppins';
}

.navbar .brand-name {
  font-weight: bold;
}
</style>