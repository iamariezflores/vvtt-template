<script setup lang="ts">

defineProps<{ msg: string }>()
</script>

<template>
  <div class="flex items-center justify-center mt-40">
    <h1 class="text-2xl font-bold">{{ msg }}</h1>
  </div>
</template>