<template>
  <section id="projects" class="py-20 px-6 bg-white max-w-5xl mx-auto">
    <h2 class="text-2xl font-bold mb-6 text-center text-gray-800">Project</h2>

    <div class="grid md:grid-cols-2 gap-6">
      <ProjectCard
        title="Dainsleif"
        image="/dainsleif.jpg"
        link="https://relaxed-axolotl-9932ff.netlify.app/"
        :tags="['Vue 3', 'Tailwind CSS', 'REST API']"
        description="Dainsleif adalah platform digital modern untuk produk dan jasa kreatif seperti UI kit dan landing page. Dibangun menggunakan Vue 3, Tailwind CSS, dan REST API, Dainsleif dirancang agar responsif, cepat, dan intuitif untuk pengguna."
      />

      <ProjectCard
        title="NexAC"
        image="/nexac.jpg"
        link="https://boisterous-babka-2d5f21.netlify.app/"
        :tags="['Vue 3', 'Tailwind CSS', 'REST API']"
        description="NexAC adalah platform e-katalog modern untuk produk pendingin ruangan (AC), lengkap dengan fitur pencarian produk, detail spesifikasi, dan pemesanan jasa servis. Fokus pada tampilan elegan dan navigasi intuitif."
      />
    </div>
  </section>
</template>

<script>
import ProjectCard from '@/components/ProjectCard.vue'

export default {
  name: 'ProjectSection',
  components: {
    ProjectCard,
  },
}
</script>
