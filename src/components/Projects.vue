<script setup lang="ts">
import ProjectLink from "./ProjectLink.vue";
</script>

<template>
  <div class="card">
    <h1> 📚 My Projects </h1>
    
    <div class="text-container">
      <ProjectLink 
          text="Wake-on-Lan telegram bot"
          url="https://github.com/linuxfight/WoL_bot"/>
      
      <ProjectLink 
          text="Telegram bot for testing Tinkoff kassa payment link generation"
          url="https://github.com/linuxfight/TestTinkoffBot"/>
      
      <ProjectLink 
          text="Minecraft launcher for Metro modpack"
          url="https://github.com/linuxfight/metro_launcher"/>
      
      <ProjectLink 
          text="A web application for the exchange of paper books"
          url="https://github.com/bookswapper"/>

      <p>
        There could be more projects, but some of them are private and I can't share them.
      </p>
    </div>
  </div>
</template>

<style scoped>
</style>