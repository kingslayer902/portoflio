<template>
  <section id="projects" class="py-20 px-6 bg-white max-w-5xl mx-auto">
    <h2 class="text-2xl font-bold mb-6 text-center text-gray-800">Project</h2>

    <div class="grid md:grid-cols-2 gap-6">
      <!-- Proyek 1 -->
      <div
        class="bg-white p-6 rounded-lg shadow transition-transform duration-300 hover:shadow-lg hover:-translate-y-1"
      >
        <h3 class="font-semibold text-lg mb-2 text-gray-800">Dainsleif</h3>
        <p class="text-sm text-gray-700 mb-4">
          Dainsleif adalah platform digital modern untuk produk dan jasa kreatif seperti UI kit dan landing page. Proyek ini dilengkapi dengan fitur interaktif seperti live chat, order tracking, dan dashboard admin tersembunyi.

Dibangun menggunakan Vue 3, Tailwind CSS, dan REST API, Dainsleif dirancang agar responsif, cepat, dan intuitif untuk pengguna.

Saat ini, sebagian konten masih berupa dummy data, namun struktur dan alur fungsionalitas sudah siap untuk diintegrasikan ke sistem backend penuh. Proyek ini merupakan cerminan dari pengalaman saya dalam membangun platform digital yang modern dan scalable.
        </p>
        <a
          href="https://relaxed-axolotl-9932ff.netlify.app/"
          target="_blank"
          class="text-blue-600 hover:underline font-medium"
        >
          Lihat Project →
        </a>
      </div>

      <!-- Proyek 2 -->
      <div
        class="bg-white p-6 rounded-lg shadow transition-transform duration-300 hover:shadow-lg hover:-translate-y-1"
      >
        <h3 class="font-semibold text-lg mb-2 text-gray-800">NexAC</h3>
        <p class="text-sm text-gray-700 mb-4">
         NexAC adalah platform e-katalog modern untuk produk pendingin ruangan (AC), lengkap dengan fitur pencarian produk, detail spesifikasi, dan pemesanan jasa servis.

Aplikasi ini dikembangkan menggunakan Vue 3, Tailwind CSS, dan REST API, dengan fokus pada tampilan yang elegan, navigasi yang intuitif, serta pengalaman pengguna yang responsif di berbagai perangkat.

Sebagian data pada platform ini masih berupa dummy, namun alur produk dan jasa sudah dapat diakses dan diuji. Proyek ini masih aktif dikembangkan dan dirancang untuk mendukung integrasi ke fitur pembayaran online serta form pemesanan berbasis WhatsApp.
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
export default {
  name: 'ProjectSection',
}
</script>
