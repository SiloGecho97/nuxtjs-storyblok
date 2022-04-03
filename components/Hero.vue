
<template>
    <section class="hero w-full mx-auto flex flex-col md:flex-row max-w-screen-xl items-center justify-center min-h-[24rem] ">
        <div class="md:my-32">
            <h1 class="text-5xl text-center">{{blok.headline}}</h1>
            <p class="text-center text-gray-800 text-xl">{{blok.description}}</p>
        </div>
    </section>
</template>
<script>
export default {
  props: {
    blok: {
      type: Object,
      required: true
    }
  }
} 
</script>

