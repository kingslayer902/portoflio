<template>
  <section id="about" class="py-20 px-6 bg-white dark:bg-gray-950 max-w-5xl mx-auto transition-colors duration-300">
    <h2 class="text-2xl font-bold mb-6 text-center text-gray-800 dark:text-gray-200">Tentang Saya</h2>
    
    <div class="grid md:grid-cols-2 gap-10">
      <div>
        <h3 class="text-xl font-semibold mb-2 text-gray-800 dark:text-gray-200">Informasi Pribadi</h3>
        <ul class="list-disc ml-5 text-sm text-gray-700 dark:text-gray-300">
          <li>Nama: Mochamad Ezra Saptiawan</li>
          <li>Tempat Lahir: Pasuruan, 22 Agustus 2003</li>
          <li>Domisili: Rawasari, Jakarta Pusat</li>
          <li>Email: saptiawanezra@gmail.com</li>
          <li>WhatsApp: 0895-0502-4468</li>
        </ul>
      </div>
      <div>
        <h3 class="text-xl font-semibold mb-2 text-gray-800 dark:text-gray-200">Kemampuan</h3>
        <ul class="list-disc ml-5 text-sm text-gray-700 dark:text-gray-300">
          <li>HTML, CSS, JavaScript, Vue</li>
          <li>Responsive Web Design</li>
          <li>Git, GitHub, Netlify, VS Code</li>
          <li>Microsoft Word, Excel, PowerPoint</li>
          <li>Komunikatif, teliti, multitasking</li>
        </ul>
      </div>
    </div>

    <div class="mt-10">
      <h3 class="text-xl font-semibold mb-4 text-gray-800 dark:text-gray-200">Pengalaman Kerja</h3>

      <div class="mb-6">
        <p class="font-medium text-gray-800 dark:text-gray-200">IFCA PROPERTY 365 (Fullstack Developer) | 2024 - 2025</p>
        <ul class="list-disc ml-5 text-sm text-gray-700 dark:text-gray-300">
          <li>Mengembangkan frontend dengan Vue.js & Tailwind CSS</li>
          <li>Membuat REST API pakai Express & MongoDB</li>
          <li>Implementasi autentikasi & dashboard admin</li>
          <li>Bug fixing dan kerja tim lewat GitHub</li>
          <li>Deployment ke Netlify & Render</li>
        </ul>
      </div>

      <div>
        <p class="font-medium text-gray-800 dark:text-gray-200">PT. Moedtjibaba & Sons (Admin) | 2023 - 2024</p>
        <ul class="list-disc ml-5 text-sm text-gray-700 dark:text-gray-300">
          <li>Mengelola dokumen dan arsip kantor</li>
          <li>Input dan rekap data administrasi</li>
          <li>Membuat laporan mingguan dan bulanan</li>
          <li>Komunikasi internal dan eksternal</li>
          <li>Pengarsipan dan penjadwalan rutin</li>
        </ul>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'AboutSection',
};
</script>
