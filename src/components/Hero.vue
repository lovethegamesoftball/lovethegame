<script setup lang="ts">
import Navbar from "./Navbar.vue";
</script>

<template>
  <div>
    <section class="hero">
      <div class="hero-head">
        <Navbar />
      </div>

      <div class="hero-body">
        <div class="container has-text-centered">
          <h1
            class="title has-text-dark has-text-weight-bold is-size-1 is-size-2-mobile"
          >
            Sarah Ogle Softball Coaching
          </h1>
          <p class="subtitle has-text-dark">
            Pitching, hitting, and fielding lessons in San Diego
          </p>

          <div class="buttons">
            <a
              href="https://koalendar.com/u/lovethegamesoftballcoaching"
              class="button is-primary centered-buttons"
            >
              <strong>Book here!</strong>
            </a>
          </div>
        </div>
      </div>
    </section>
    <section class="hero is-medium hero-image"></section>
  </div>
</template>

<style scoped>
.centered-buttons {
  margin-left: auto;
  margin-right: auto;
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
  background-image: url("../hero-image-medium.png");
  background-repeat: no-repeat;
  background-size: cover;

  @media (min-width: 1000px) {
    background-image: url("../hero-image-wide.png");
  }

  @media (max-width: 680px) {
    background-image: url("../hero-image-narrow.png");
  }
}
</style>
