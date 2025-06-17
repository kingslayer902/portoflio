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
         Proyek ini dirancang untuk menciptakan platform yang mudah digunakan dengan integrasi berbagai fitur interaktif. Salah satu tantangan terbesar adalah mengelola koneksi live-chat secara real-time dan memastikan pengalaman pengguna yang mulus di berbagai perangkat. Dengan menggunakan Vue 3 dan Tailwind CSS, saya berhasil membangun antarmuka yang responsif dan estetik, sementara REST API memungkinkan integrasi yang lancar dengan backend. Proyek ini masih dalam tahap pengembangan, dengan rencana untuk menambah fitur lebih lanjut dan penyempurnaan UX/UI.
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
      
      <div
        class="bg-gray-100 p-6 rounded-lg shadow hover:shadow-lg transition"
      >
        <h3 class="font-semibold text-lg mb-2 text-gray-800">NexAC</h3>
        <p class="text-sm text-gray-700 mb-4">
          Nexac adalah platform e-katalog untuk produk AC dengan integrasi fitur pencarian produk, detail spesifikasi, serta layanan pemesanan jasa servis. Dibangun dengan Vue 3 dan Tailwind CSS, aplikasi ini dirancang untuk memastikan pengalaman pengguna yang responsif dan mudah dinavigasi di berbagai perangkat. Salah satu tantangan utama dalam proyek ini adalah menyusun katalog produk secara efisien, agar pengguna bisa dengan mudah menemukan produk yang sesuai dengan kebutuhan mereka. Proyek ini masih dalam tahap pengembangan, dengan rencana untuk menambahkan fitur pemesanan online dan sistem pembayaran.
        </p>
        <a
          href="https://boisterous-babka-2d5f21.netlify.app/"
          target="_blank"
          class="text-blue-600 hover:underline font-medium"
        >
          Lihat Project →
        </a>
      </div>
      
    </div>
  </section>
</template>

<script>
export default { name: 'ProjectSection' }
</script>
