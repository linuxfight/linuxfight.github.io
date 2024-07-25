<script setup lang="ts">

</script>

<template>
  <div class="card">
    <div>
      <h1> 📢 My accounts </h1>
    </div>
    <div class="socials">
      <a href="https://github.com/linuxfight" target="_blank">
        <img src="../assets/github.svg" class="logo" alt="My github"/>
      </a>
      <a href="https://t.me/linuxfight" target="_blank">
        <img src="../assets/telegram.svg" class="logo" alt="My telegram"/>
      </a>
    </div>
  </div>
</template>

<style scoped>

.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
</style>