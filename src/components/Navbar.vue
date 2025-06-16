<template>
  <header class="fixed top-0 left-0 w-full bg-white shadow z-50">
    <nav class="max-w-5xl mx-auto px-6 py-4 flex justify-between items-center" aria-label="Navigasi utama">
      <h1 class="text-xl font-bold text-blue-600">Ezra.dev</h1>
      <ul class="flex space-x-6 text-sm font-medium">
        <li><a href="#hero" class="hover:text-blue-600 transition cursor-pointer">Home</a></li>
        <li><a href="#about" class="hover:text-blue-600 transition cursor-pointer">Tentang</a></li>
        <li><a href="#projects" class="hover:text-blue-600 transition cursor-pointer">Project</a></li>
        <li><a href="#contact" class="hover:text-blue-600 transition cursor-pointer">Kontak</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'Navbar',
};
</script>

<style>
html {
  scroll-behavior: smooth;
}
</style>
