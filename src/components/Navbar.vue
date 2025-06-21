<template>
  <header
    :class="['fixed top-0 left-0 w-full z-50 transition duration-300 backdrop-blur bg-white/90', { 'shadow-md': scrolled }]"
  >
    <nav class="max-w-5xl mx-auto px-6 py-4 flex justify-between items-center" aria-label="Navigasi utama">
      <h1 class="text-xl font-bold text-blue-600">Ezra.dev</h1>

      <!-- Tombol Hamburger (Mobile) -->
      <button @click="isOpen = !isOpen" class="md:hidden focus:outline-none">
        <svg v-if="!isOpen" xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-gray-800" fill="none"
          viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
            d="M4 6h16M4 12h16M4 18h16" />
        </svg>
        <svg v-else xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 text-gray-800" fill="none"
          viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
            d="M6 18L18 6M6 6l12 12" />
        </svg>
      </button>

      <!-- Menu Desktop -->
      <ul class="hidden md:flex space-x-6 text-sm font-medium text-gray-800">
        <li><a href="#hero" class="hover:text-blue-600 transition">Home</a></li>
        <li><a href="#about" class="hover:text-blue-600 transition">Tentang</a></li>
        <li><a href="#projects" class="hover:text-blue-600 transition">Project</a></li>
        <li><a href="#footer" class="hover:text-blue-600 transition">Kontak</a></li>
      </ul>
    </nav>

    <!-- Menu Mobile -->
    <transition name="fade">
      <ul v-if="isOpen" class="md:hidden bg-white px-6 pb-4 space-y-4 text-sm font-medium text-gray-800 border-t border-gray-200">
        <li><a href="#hero" class="block hover:text-blue-600" @click="closeMenu">Home</a></li>
        <li><a href="#about" class="block hover:text-blue-600" @click="closeMenu">Tentang</a></li>
        <li><a href="#projects" class="block hover:text-blue-600" @click="closeMenu">Project</a></li>
        <li><a href="#footer" class="block hover:text-blue-600" @click="closeMenu">Kontak</a></li>
      </ul>
    </transition>
  </header>
</template>

<script>
export default {
  name: 'Navbar',
  data() {
    return {
      isOpen: false,
      scrolled: false,
    }
  },
  mounted() {
    window.addEventListener('scroll', this.handleScroll)
  },
  beforeUnmount() {
    window.removeEventListener('scroll', this.handleScroll)
  },
  methods: {
    handleScroll() {
      this.scrolled = window.scrollY > 10
    },
    closeMenu() {
      this.isOpen = false
    }
  }
}
</script>

<style scoped>
.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.2s ease;
}
.fade-enter-from,
.fade-leave-to {
  opacity: 0;
}
html {
  scroll-behavior: smooth;
}
</style>
