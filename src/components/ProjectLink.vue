<script setup lang="ts">
defineProps({
  text: String,
  url: String
})
</script>

<template>
  <p>
    {{text}} -
    <a :href="url">
      link
    </a>
  </p>
</template>

<style scoped>

</style>