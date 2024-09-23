<script setup lang="ts">
import About from "./components/About.vue";
import Hero from "./components/Hero.vue";
import SiteFooter from "./components/SiteFooter.vue";
</script>

<template>
  <div class="page-container">
    <div class="body-container"><Hero /> <About /><SiteFooter /></div>
  </div>
</template>

<style scoped>
.page-container {
  width: 100%;
}

.body-container {
  margin-left: auto;
  margin-right: auto;
  padding: 12px;
  width: 100%;
  max-width: 1028px;
}
</style>
