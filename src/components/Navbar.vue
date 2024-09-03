<script setup lang="ts"></script>

<template>
  <nav class="navbar" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">
      <a class="navbar-item logo" href="https://lovethegamesoftball.com">
        <img src="../assets/hitting-logo.png" />
      </a>

      <a
        role="button"
        class="navbar-burger"
        aria-label="menu"
        aria-expanded="false"
        data-target="navbarBasicExample"
      >
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
      </a>
    </div>

    <div id="navbarBasicExample" class="navbar-menu">
      <div class="navbar-start"></div>

      <div class="navbar-end">
        <a class="navbar-item">Lessons</a>
        <a class="navbar-item"> About </a>
        <div class="navbar-item">
          <div class="buttons">
            <a class="button is-primary">
              <strong>Book lesson</strong>
            </a>
          </div>
        </div>
      </div>
    </div>
  </nav>
</template>

<style scoped>
.logo {
  margin-left: 20px;
}
</style>
