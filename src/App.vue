<template>
  <div class="font-sans text-gray-900 dark:text-gray-100 bg-white ">
    <Navbar />
    <HeroSection />
    <ProjectSection />
    <AboutSection />
    <FooterSection />
  </div>
</template>

<script>
import HeroSection from './components/HeroSection.vue'
import AboutSection from './components/AboutSection.vue'
import ProjectSection from './components/ProjectSection.vue'
import FooterSection from './components/FooterSection.vue'
import Navbar from './components/Navbar.vue'

export default {
  name: 'App',
  components: {
    HeroSection,
    AboutSection,
    ProjectSection,
    FooterSection,
    Navbar
  }
}
</script>
