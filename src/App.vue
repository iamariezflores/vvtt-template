<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="flex items-center justify-center">
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" alt="Vite logo" class="h-40 mt-20 mr-20"/>
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" alt="Vue logo" class="h-40 mr-20 mt-20"/>
    </a>
    <a href="https://www.typescriptlang.org/" target="_blank">
      <img src="./assets/typescript.svg" alt="Typescript logo" class="h-40 mr-20 mt-20"/>
    </a>
    <a href="https://tailwindcss.com/" target="_blank">
      <img src="./assets/tailwindcss.png" alt="TaiwindCSS logo" class="h-40 mt-20"/>
    </a>
  </div>
  <HelloWorld msg="Vite + Vue + Typescript + TailwindCSS" />
</template>
