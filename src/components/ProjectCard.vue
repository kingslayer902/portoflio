<template>
  <div
    class="bg-white p-6 rounded-lg shadow transition-transform duration-300 hover:shadow-lg hover:-translate-y-1"
  >
    <img
      v-if="image"
      :src="image"
      :alt="title"
      class="w-full h-40 object-cover rounded mb-4"
    />
    <h3 class="font-semibold text-lg mb-2 text-gray-800">{{ title }}</h3>
    <p class="text-sm text-gray-700 mb-4">
      {{ description }}
    </p>
    <div class="flex flex-wrap gap-2 mb-4">
      <span
        v-for="(tag, index) in tags"
        :key="index"
        class="text-xs bg-blue-100 text-blue-700 px-2 py-1 rounded"
      >
        {{ tag }}
      </span>
    </div>
    <a
      :href="link"
      target="_blank"
      class="text-blue-600 hover:underline font-medium"
    >
      Lihat Project →
    </a>
  </div>
</template>

<script>
export default {
  name: "ProjectCard",
  props: {
    title: String,
    description: String,
    link: String,
    image: String,
    tags: Array
  },
}
</script>
