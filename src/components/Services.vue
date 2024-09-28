<script setup lang="ts"></script>

<template>
  <section class="services">
    <h2
      class="title has-text-dark has-text-weight-bold is-size-3 has-text-centered-mobile"
    >
      Services
    </h2>
    <p>I offer private or group lessons (up to 4)</p>
    <br />
    <div class="columns is-multiline is-mobile">
      <div class="column is-half-mobile">
        <img class="image" src="../../hero-image-narrow.png" alt="Pitching" />
        <br />
        <p>Pitching</p>
      </div>
      <div class="column is-half-mobile">
        <img class="image" src="../../hero-image-narrow.png" alt="Hitting" />
        <br />
        <p>Hitting</p>
      </div>
      <div class="column is-half-mobile">
        <img class="image" src="../../hero-image-narrow.png" alt="fielding" />
        <br />
        <p>Fielding</p>
      </div>
      <div class="column is-half-mobile">
        <img class="image" src="../../hero-image-narrow.png" alt="Catching" />
        <br />
        <p>Catching</p>
      </div>
    </div>
  </section>
</template>

<style scoped>
.services {
  padding: 24px;
}

.image {
  @media (max-width: 780px) {
    display: block;
    margin-left: auto;
    margin-right: auto;
  }

  border-radius: 8px;
  max-height: 200px;
}
</style>
