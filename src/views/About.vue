<template>
  <section class="p-10 max-w-3xl mx-auto animate-fade-in">
    <h2 class="text-2xl font-bold mb-4 text-blue-700">Tentang Saya</h2>
    <div class="flex flex-col md:flex-row gap-6 items-center mb-6">
      <img :src="fotoEzra" alt="Foto Ezra" class="rounded-full w-32 border shadow-md" />
      <p>
        Saya adalah individu yang teliti, cekatan, dan bertanggung jawab. Berpengalaman sebagai admin kantor dan sedang mengembangkan keterampilan di bidang frontend development.
      </p>
    </div>

    <div class="grid md:grid-cols-2 gap-6">
      <div>
        <h3 class="text-xl font-semibold mb-2 text-blue-600">Informasi Pribadi</h3>
        <ul class="list-disc ml-5">
          <li>Nama: Mochamad Ezra Saptiawan</li>
          <li>Tempat Lahir: Pasuruan, 22 Agustus 2003</li>
          <li>Domisili: Rawasari, Jakarta Pusat</li>
          <li>Email: <a href="mailto:saptiawanezra@gmail.com" class="text-blue-600 hover:underline">saptiawanezra@gmail.com</a></li>
          <li>WhatsApp: <a href="https://wa.me/6289505024468" class="text-green-600 hover:underline" target="_blank">0895-0502-4468</a></li>
        </ul>
      </div>
      <div>
        <h3 class="text-xl font-semibold mb-2 text-blue-600">Kemampuan</h3>
        <ul class="list-disc ml-5">
          <li>HTML, CSS, JavaScript, Vue</li>
          <li>Responsive Web Design</li>
          <li>Git, GitHub, Netlify, VS Code</li>
          <li>Microsoft Word, Excel, PowerPoint</li>
          <li>Komunikatif, teliti, multitasking</li>
        </ul>
      </div>
    </div>

    <div class="mt-6">
      <h3 class="text-xl font-semibold mb-2 text-blue-600">Pengalaman Kerja</h3>

      <div class="mb-4">
        <p class="font-medium">PT. Moedtjibaba & Sons (Admin) | 2023 - 2024</p>
        <ul class="list-disc ml-5">
          <li>Mengelola dokumen dan arsip kantor</li>
          <li>Input dan rekap data administrasi</li>
          <li>Membuat laporan mingguan dan bulanan</li>
          <li>Komunikasi internal dan eksternal</li>
          <li>Pengarsipan dan penjadwalan rutin</li>
        </ul>
      </div>

      <div>
        <p class="font-medium">IFCA PROPERTY 365 (Fullstack Developer) | 2024 - 2025</p>
        <ul class="list-disc ml-5">
          <li>Mengembangkan fitur frontend menggunakan Vue.js dan Tailwind CSS</li>
          <li>Membuat REST API menggunakan Express dan MongoDB</li>
          <li>Implementasi autentikasi dan dashboard admin</li>
          <li>Bug fixing dan kolaborasi dengan tim menggunakan GitHub</li>
          <li>Deployment ke server produksi menggunakan Netlify dan Render</li>
        </ul>
      </div>
    </div>
  </section>
</template>

<script setup>
const fotoEzra = `${import.meta.env.BASE_URL}ezra.jpg`
</script>
