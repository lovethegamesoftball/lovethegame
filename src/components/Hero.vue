<script setup lang="ts">
import Navbar from "./Navbar.vue";
</script>

<template>
  <div class="hero-container">
    <section class="hero">
      <div class="hero-head"><Navbar /></div>

      <div class="hero-body">
        <div class="container has-text-centered">
          <h1 class="title has-text-dark has-text-weight-bold is-size-2">
            Sarah Ogle Softball Coaching
          </h1>
          <p class="subtitle has-text-dark">
            Pitching, hitting, and fielding lessons in San Diego
          </p>
        </div>
      </div>
    </section>
    <section class="hero is-medium hero-image"></section>
  </div>
</template>

<style scoped>
.hero-container {
  width: 100%;
}

.booking-color {
  color: rgb(15, 139, 141);
}

.hero-image {
  height: 40vh;
  margin-left: auto;
  margin-right: auto;
  max-width: 1000px;
  background-attachment: scroll;
  background-image: url("../assets/hero-image-medium.png");
  background-repeat: no-repeat;
  background-size: cover;
  @media (min-width: 1000px) {
    background-image: url("../assets/hero-image-wide.png");
  }
  @media (max-width: 680px) {
    background-image: url("../assets/hero-image-narrow.png");
  }
}
</style>
