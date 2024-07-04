<template>
  <section class="About">
    <div class="container">
      <div class="image-container">
        <img src="../assets/profile.png" alt="About" class="img-fluid">
      </div>
      <div class="text-wrapper">
        <p>QWERTYUI</p>
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
}

.image-container{
}

img
{
  width: 50%;
  border-radius: 50px
}

.text-wrapper
{
  margin-right: 10rem;
}
</style>
