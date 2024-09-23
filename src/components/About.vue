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
      <h2 class="title has-text-dark has-text-weight-bold is-size-3 has-text-centered-mobile">
        Meet Coach Sarah
      </h2>
      <div class="columns">
        <div class="column is-one-third">
          <img class="portrait" src="../assets/portrait.jpg"
            alt="A photo of coach sarah standing in front of a view of la jolla" />
        </div>
        <div class="column text-about">

          <p>I have over five years of softball coaching experience in San Diego working with athletes ages 7-17. My
            pitching coach, Bill Corbett, instilled this motto in me: "Always love the game". I always seek to foster a
            love for softball in my clients and make sure they have fun while improving each day.</p>
          <br>

          <p>My favorite memories growing up are from playing Peninsula Breakers All-stars for Coach Dad, especially
            qualifying for our first State tournament. I played travel softball for Power Surge and Renegades, including
            winning the 16U Colorado Sparkler Tournament.</p>
          <br>

          <p>At Carleton College, I pitched and played 2B while earning a Geology degree in 2019. As one of the team
            captains my senior year, I helped lead our team to break the Carleton single-season win record. I am now a
            Ph.D. Candidate in Climate Science at UCSD. It has been a joy to coach in my hometown and work with the next
            generation of young
            athletes!</p>



        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
.about {
  padding: 0px 24px 24px 24px;
}

.text-about {
  font-size: 1.1rem;
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
