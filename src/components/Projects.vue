<script async setup lang="ts">
const response = await fetch("https://api.github.com/users/linuxfight/repos");
const repos = await response.json();
</script>

<template>
  <h1> My Projects </h1>

  <li v-for="repo in repos">
    <a :href="repo.html_url"> {{ repo.name }} </a> - {{ repo.description }}
  </li>
</template>

<style scoped>

</style>