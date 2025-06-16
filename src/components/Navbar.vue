<template>
  <header class="fixed top-0 left-0 w-full bg-white shadow z-50">
    <nav class="max-w-5xl mx-auto px-6 py-4 flex justify-between items-center">
      <h1 class="text-xl font-bold text-blue-600">Ezra.dev</h1>
      <ul class="flex space-x-6 text-sm font-medium">
        <li><a href="#hero" class="hover:text-blue-600 transition">Home</a></li>
        <li><a href="#about" class="hover:text-blue-600 transition">Tentang</a></li>
        <li><a href="#projects" class="hover:text-blue-600 transition">Project</a></li>
        <li><a href="#contact" class="hover:text-blue-600 transition">Kontak</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'Navbar',
};
</script>
