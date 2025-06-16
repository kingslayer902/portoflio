<template>
  <main class="font-sans text-gray-800 bg-gray-50 min-h-screen">
    <Navbar />
    <RouterView />
    <Footer />
  </main>
</template>

<script setup>
import Navbar from './components/Navbar.vue'
import Footer from './components/Footer.vue'
</script>