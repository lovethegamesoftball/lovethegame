<script setup lang="ts">
import Navbar from "./Navbar.vue";
</script>

<template>
  <div class="hero-container">
    <section class="hero is-halfheight hero-image">
      <div class="hero-head"><Navbar /></div>

      <div class="hero-body">
        <div class="container has-text-centered">
          <p class="title has-text-light">Half height hero</p>
          <p class="subtitle has-text-light">Half height subtitle</p>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
.hero-container {
  width: 100%;
  background-color: rgb(203, 204, 215);
}
.hero-image {
  margin-left: auto;
  margin-right: auto;
  max-width: 1248px;
  background-attachment: scroll;
  background-image: url("../assets/running.webp");
  background-repeat: no-repeat;
  background-position-x: 20%;
  background-size: cover;
  color: white;
}
</style>
