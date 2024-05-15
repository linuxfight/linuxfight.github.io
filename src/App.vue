<script setup lang="ts">
import Socials from "./components/Socials.vue";
import Bio from "./components/Bio.vue";
import Hello from "./components/Hello.vue";
import Projects from "./components/Projects.vue";
</script>

<template>
  <div id="app">
    <Hello/>
    <Bio/>
    <Suspense>
      <Projects/>
    </Suspense>
    <Socials/>
  </div>
</template>

<style scoped>
</style>
