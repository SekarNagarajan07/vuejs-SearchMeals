<template>
  <a
    :href="href"
    target="_blank"
    class="mb-3 px-2 py-1 rounded border-2 text-white border-red-600 bg-red-600 hover:bg-red-600 transition-colors"
    ><slot>YouTube</slot></a
  >
</template>

<script setup>
const props = defineProps({
  href: String
})
</script>

<style></style>
