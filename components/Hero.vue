
<template>
  <section
    class="
      mt-10
      mx-auto
      max-w-6xl
      px-4
      sm:mt-12 sm:px-6
      md:my-16
      lg:my-20 lg:px-8
      xl:my-28
    "
  >
    <div class="sm:text-center lg:text-center">
      <h1
        class="
          text-4xl
          tracking-none
          font-extrabold
          text-gray-800
          sm:text-5xl
          md:text-6xl
        "
      >
        <span class="block xl:inline">{{ blok.headline }}</span>
      </h1>
      <p
        class="
          mt-3
          text-base text-gray-500
          sm:mt-5 sm:text-lg sm:max-w-xl sm:mx-auto
          md:mt-5 md:text-xl
          lg:mx-auto
          text-center
        "
      >
        {{blok.description}}
      </p>
      <div class="mt-5 sm:mt-8 sm:flex sm:justify-center lg:justify-center">
        <div class="rounded-md shadow">
          <a
            href="#"
            class="
              w-full
              flex
              items-center
              justify-center
              px-8
              py-3
              border border-transparent
              text-base
              font-medium
              rounded-md
              text-white
              bg-indigo-600
              hover:bg-indigo-700
              md:py-4 md:text-lg md:px-10
            "
          >
            {{blok.more_cta_label}}
          </a>
        </div>
      </div>
    </div>
    
  </section>
</template>
<script>
export default {
  props: {
    blok: {
      type: Object,
      required: true,
    },
  },
};
</script>

