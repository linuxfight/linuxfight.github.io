<script setup lang="ts">
import ProjectLink from "./ProjectLink.vue";
</script>

<template>
  <div class="card">
    <h1> 📚 My Projects </h1>
    
    <div class="container text-container">
      <ProjectLink 
          text="Telegram WoL bot"
          url="https://github.com/linuxfight/wol-e"/>

      <ProjectLink
          text="Go Web App template"
          url="https://github.com/linuxfight/webTemplate"/>
      
      <ProjectLink 
          text="A web application for the exchange of paper books"
          url="https://github.com/bookswapper"/>

      <ProjectLink
          text="Telegram Mini App for splitting and managing expenses"
          url="https://github.com/SplitOnly"/>
    </div>
  </div>
</template>

<style scoped>
</style>
