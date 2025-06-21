<template>
  <section id="about" class="py-20 px-6 bg-white text-gray-800 max-w-5xl mx-auto">
    <div class="text-center mb-10">
      <p class="text-sm uppercase tracking-widest text-blue-600 font-semibold">Profil Singkat</p>
      <h2 class="text-2xl font-bold mt-2">Tentang Saya ✨</h2>
    </div>

    <div class="grid md:grid-cols-2 gap-10">
      <!-- Informasi Pribadi -->
      <div>
        <h3 class="text-xl font-semibold mb-2">👤 Informasi Pribadi</h3>
        <ul class="list-disc ml-5 text-sm text-gray-700 space-y-1">
          <li><strong>Nama:</strong> Mochamad Ezra Saptiawan</li>
          <li><strong>Tempat Lahir:</strong> Pasuruan, 22 Agustus 2003</li>
          <li><strong>Domisili:</strong> Rawasari, Jakarta Pusat</li>
          <li>
            <strong>Email:</strong>
            <a href="mailto:saptiawanezra@gmail.com" class="text-blue-600 underline">
              saptiawanezra@gmail.com
            </a>
          </li>
        </ul>
      </div>

      <!-- Kemampuan -->
      <div>
        <h3 class="text-xl font-semibold mb-2">🎓 Kemampuan</h3>
        <ul class="list-disc ml-5 text-sm text-gray-700 space-y-1">
          <li><strong>Frontend:</strong> HTML, CSS, JavaScript, Vue</li>
          <li><strong>UI/UX:</strong> Responsive Web Design</li>
          <li><strong>Tools:</strong> Git, GitHub, Netlify, VS Code</li>
          <li><strong>Office:</strong> Microsoft Word, Excel, PowerPoint</li>
          <li><strong>Soft Skill:</strong> Komunikatif, teliti, multitasking</li>
        </ul>
      </div>
    </div>

    <!-- Pengalaman Kerja -->
    <div class="mt-16">
      <h3 class="text-xl font-semibold mb-4">💼 Pengalaman Kerja</h3>

      <div class="mb-6">
        <p class="font-medium">IFCA PROPERTY 365 <span class="text-sm text-gray-500">(Fullstack Developer | 2024 - 2025)</span></p>
        <ul class="list-disc ml-5 text-sm text-gray-700 space-y-1">
          <li>Mengembangkan frontend dengan <strong>Vue.js</strong> & <strong>Tailwind CSS</strong></li>
          <li>Membuat <strong>REST API</strong> pakai Express & MongoDB</li>
          <li>Implementasi <strong>autentikasi</strong> & dashboard admin</li>
          <li>Bug fixing dan kerja tim lewat GitHub</li>
          <li>Deployment ke <strong>Netlify</strong> & <strong>Render</strong></li>
        </ul>
      </div>

      <div>
        <p class="font-medium">PT. Moedtjibaba & Sons <span class="text-sm text-gray-500">(Admin | 2023 - 2024)</span></p>
        <ul class="list-disc ml-5 text-sm text-gray-700 space-y-1">
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
}
</script>
