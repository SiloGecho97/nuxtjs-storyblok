<template>
  <div v-editable="blok" class="pb-8 mb-6 text-start p-4 bg-gray-100">
    <img
      class="h-10 w-10 mb-4 object-cover"
      :src="blok.icons.filename" />
    <h3 class="text-3xl font-bold my-2">{{ blok.name }}</h3>
    <p>{{ blok.description }}</p>
  </div>
</template>

<script>
export default {
  name: "payment",
  props: {
    blok: {
      type: Object,
      required: true,
    },
  },
};
</script>
