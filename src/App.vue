<template>
  <div>
    <Navbar />

    <!-- Section per bagian (pakai id buat navigasi scroll) -->
    <HeroSection />
    <AboutSection />
    <ProjectsSection/>
    <Footer />
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import AboutSection from './components/AboutSection.vue';
import ProjectsSection from './components/ProjectSection.vue';
import Footer from './components/Footer.vue';
import HeroSection from './components/HeroSection.vue';

export default {
  components: {
    Navbar,
    HeroSection,
    AboutSection,
    ProjectsSection,
    Footer
  }
};
</script>
