<template>
  <section
    id="hero"
    class="min-h-screen flex flex-col items-center justify-center text-center p-6 bg-white"
  >
    <img
      src="/ezra.jpg"
      alt="Foto Ezra"
      class="w-32 h-32 rounded-full border-4 border-gray-300 shadow mb-4 animate-fade-in"
    />
    <h1 class="text-3xl md:text-5xl font-bold mb-2 text-gray-800 animate-slide-in">
      Mochamad Ezra Saptiawan
    </h1>
    <p class="text-lg md:text-xl text-gray-700 animate-fade-in delay-200">
      Frontend & Fullstack Developer · Administrator Kantor
    </p>

    <div class="flex flex-wrap justify-center gap-4 mt-6 animate-fade-in delay-300">
      <a
        href="#projects"
        class="px-6 py-3 bg-blue-600 text-white font-semibold rounded-lg shadow hover:bg-blue-700 hover:scale-105 transition-all duration-300"
      >
        Lihat Proyek Saya
      </a>

      <a
        href="/cv-ezra.pdf"
        download
        class="px-6 py-3 bg-gray-200 text-gray-800 font-semibold rounded-lg shadow hover:bg-gray-300 hover:scale-105 transition-all duration-300"
      >
        Download CV
      </a>

      <a
        href="mailto:saptiawanezra@gmail.com"
        class="px-6 py-3 border border-blue-600 text-blue-600 font-semibold rounded-lg hover:bg-blue-50 hover:scale-105 transition-all duration-300"
      >
        Contact Me
      </a>
    </div>
  </section>
</template>

<script>
export default {
  name: "HeroSection",
};
</script>

<style scoped>
@keyframes fade-in {
  from {
    opacity: 0;
    transform: translateY(10px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes slide-in {
  from {
    opacity: 0;
    transform: translateY(-20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

.animate-fade-in {
  animation: fade-in 0.8s ease forwards;
}

.animate-slide-in {
  animation: slide-in 1s ease forwards;
}

.delay-200 {
  animation-delay: 0.2s;
}

.delay-300 {
  animation-delay: 0.3s;
}
</style>
