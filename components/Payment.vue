<template>
  <div
    v-editable="blok"
    class="pb-8 mb-6 font-bold text-center">
    <img
      class="h-48 w-full mb-4 object-cover"
      :src="blok.icon.filename" />
    <h3 class="text-5xl">{{ blok.name }}</h3>
  </div>
</template>

<script>
export default {
    name:'payment',
  props: {
    blok: {
      type: Object,
      required: true
    }
  }
}
</script>
