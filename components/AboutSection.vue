<template>
  <section class="About">
    <div class="container">
      <div class="image-container">
        <img src="../assets/profile.png" alt="About" class="img-fluid">
      </div>
      <div class="text-wrapper" >
        <p>Hi There!, I'm</p>
        <h2>Muhammad Raditya </h2>
        <p>Full Stack Programmer</p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'AboutSection'
}
</script>

<style scoped>
.about {
  padding: 50px 0;
}

.container
{
  margin-top: 20px;
  display: flex;
  align-items: center; /* Center vertically */
  justify-content: space-between; /* Space between elements */
  position: relative;
  margin-bottom: 20px;
}

.image-container{
}

img
{
  width: 70%;
  border-radius: 50px
}

.text-wrapper
{
  margin-right: 8rem;
  width: 40rem;
}
</style>
