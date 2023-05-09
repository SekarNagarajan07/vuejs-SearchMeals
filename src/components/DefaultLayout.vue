<template>
  <NavBar />
  <main>
    <div class="max-w-[1200px] mx-auto">
      <router-view />
    </div>
  </main>
</template>

<script setup>
import NavBar from "/src/components/NavBar.vue";
</script>