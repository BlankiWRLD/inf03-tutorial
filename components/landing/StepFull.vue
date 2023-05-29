<template>
    <div class="max-w-[280px] xl:max-w-[363px] space-y-6 sm:space-y-3 text-center">
      <img 
        :src="require(`~/assets/img/getting-started/${step.img}`)" 
        class="max-w-[245px] mx-auto cursor-pointer"
        @click="showImage = true"
        alt=""
      />
      <h3 class="text-xl text-neutral-800 font-semibold">{{ step.title }}</h3>
      <p class="text-sm text-gray-700 leading-relaxed">
        {{ step.description }}
      </p>
  
      <!-- Overlay for full-screen image -->
      <div 
        v-if="showImage" 
        class="fixed inset-0 bg-black bg-opacity-75 flex items-center justify-center z-50 w-screen h-screen"
        @click="showImage = false"
      >
        <img 
          :src="require(`~/assets/img/getting-started/${step.img}`)" 
          class="max-w-full max-h-full"
          alt=""
        />
      </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'LandingStepFull',
    props: {
      step: {
        type: Object,
        required: true,
      },
    },
    data() {
      return {
        showImage: false,
      };
    },
  }
  </script>
  