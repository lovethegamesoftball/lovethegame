<script setup lang="ts">
const currentYear = new Date().getFullYear();
</script>

<template>
  <footer class="footer">
    ©{{ currentYear }} Sarah Ogle Softball Coaching
  </footer>
</template>

<style scoped>
.footer {
  margin-top: 128px;
  margin-bottom: 24px;
  padding: 24px;
  background-color: rgb(229, 229, 237);
  color: rgb(148, 146, 146);
  text-align: center;
}
</style>
