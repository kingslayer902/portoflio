<template>
  <footer class="bg-white text-gray-700 py-10 px-6 mt-16 border-t border-gray-200" id="footer">
    <div class="max-w-4xl mx-auto text-center">
      <h3 class="text-2xl font-semibold mb-2 text-gray-800">Hubungi Saya</h3>
      <p class="text-sm text-gray-600 mb-6">Terima kasih telah mengunjungi portofolio saya. Jangan ragu untuk terhubung!</p>

      <p class="mb-4 text-sm sm:text-base">
        Email:
        <a
          href="mailto:saptiawanezra@gmail.com"
          class="text-blue-600 hover:underline"
        >
          saptiawanezra@gmail.com
        </a>
      </p>

      <div class="flex justify-center gap-4 mt-4 mb-8">
        <a href="https://github.com/kingslayer902" target="_blank" class="hover:scale-110 transition">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="GitHub" class="w-6 h-6" />
        </a>
        <a href="https://phenomenal-tulumba-c5d90f.netlify.app" target="_blank" class="hover:scale-110 transition">
          <img src="https://api.iconify.design/simple-icons/netlify.svg" alt="Netlify" class="w-6 h-6" />
        </a>
      </div>

      <p class="text-xs text-gray-500">
        &copy; 2025 Mochamad Ezra Saptiawan. All rights reserved.
      </p>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterSection",
};
</script>
