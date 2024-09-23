<script setup lang="ts"></script>

<template>
  <div class="about">
    <section class="hero">
      <div class="hero-body">
        <p class="title has-text-centered">
          Professional softball coaching to support athletes to <br />love the
          game, work hard, communicate better,<br />and improve skills each day.
        </p>
      </div>
    </section>
    <section class="meet">
      <h2
        class="title has-text-dark has-text-weight-bold is-size-3 has-text-centered-mobile"
      >
        Meet Coach Sarah
      </h2>
      <div class="columns">
        <div class="column is-one-third">
          <img
            class="portrait"
            src="../assets/portrait.jpg"
            alt="A photo of coach sarah standing in front of a view of la jolla"
          />
        </div>
        <div class="column">
          I provide private and small group softball pitching, hitting, and
          defense lessons to athletes ages 7-18. My pitching coach, Bill
          Corbett, instilled this motto in me: "Always love the game". Thus, I
          seek to foster a love for softball in my clients while they have fun
          and improve each day. My college softball pitching and over five years
          of softball coaching experience have prepared me to provide high-level
          softball instruction.
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
.about {
  padding: 0px 24px 24px 24px;
}

.meet {
  padding: 24px;
  border-radius: 12px;
  border: 3px double rgb(15, 139, 141);
}
.portrait {
  @media (max-width: 780px) {
    display: block;
    margin-left: auto;
    margin-right: auto;
  }

  border-radius: 12px;
  max-height: 400px;
}
</style>
