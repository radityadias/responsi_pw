<script setup>
  import MyHeader from '../components/myHeader.vue';
</script>

<template>
  <div id="app">
      <MyHeader/>
      <AboutSection/>
      <HeroSection />
  </div>
</template>

<script>
import HeroSection from '~/components/HeroSection.vue';
import AboutSection from '~/components/AboutSection.vue';
import ProjectsSection from '~/components/ProjectsSection.vue';
import ContactSection from '~/components/ContactSection.vue';
import myHeader from '../components/myHeader.vue';

export default {
  components: {
    
    HeroSection,
  }
}
</script>./Index.vue
