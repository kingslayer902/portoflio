<template>
  <section id="projects" class="py-20 px-6 bg-white max-w-5xl mx-auto">
    <h2 class="text-2xl font-bold mb-6 text-center text-gray-800">Project</h2>

    <div class="grid md:grid-cols-2 gap-6">
      <!-- Proyek terbaru -->
      <div
        class="bg-gray-100 p-6 rounded-lg shadow hover:shadow-lg transition"
      >
        <h3 class="font-semibold text-lg mb-2 text-gray-800">Dainsleif</h3>
        <p class="text-sm text-gray-700 mb-4">
          Web aplikasi dengan fitur login, live‑chat, katalog produk, dan profil
          pengguna. Dibuat dengan Vue 3, Tailwind CSS, dan REST API.
        </p>
        <a
          href="https://relaxed-axolotl-9932ff.netlify.app/"
          target="_blank"
          class="text-blue-600 hover:underline font-medium"
        >
          Lihat Project →
        </a>
      </div>

      <!-- Contoh slot project lain (tinggal buka komentar & ganti konten) -->
      <!--
      <div
        class="bg-gray-100 p-6 rounded-lg shadow hover:shadow-lg transition"
      >
        <h3 class="font-semibold text-lg mb-2 text-gray-800">NexAC</h3>
        <p class="text-sm text-gray-700 mb-4">
          E‑Katalog AC lengkap dengan fitur produk & jasa servis.
        </p>
        <a
          href="https://phenomenal-tulumba-c5d90f.netlify.app/"
          target="_blank"
          class="text-blue-600 hover:underline font-medium"
        >
          Lihat Project →
        </a>
      </div>
      -->
    </div>
  </section>
</template>

<script>
export default { name: 'ProjectSection' }
</script>
