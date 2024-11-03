<script setup lang="ts">
import ProjectLink from "./ProjectLink.vue";
</script>

<template>
  <div class="card">
    <h1> 📚 My Projects </h1>
    
    <div class="container text-container">
      <ProjectLink 
          text="Telegram WoL bot"
          url="https://github.com/linuxfight/WoL_bot"/>

      <ProjectLink
          text="Discord music bot"
          url="https://github.com/linuxfight/DiscordMusicBot"/>

      <ProjectLink
          text="Go Web App template"
          url="https://github.com/linuxfight/webTemplate"/>
      
      <ProjectLink 
          text="Telegram bot for TBank Kassa"
          url="https://github.com/linuxfight/TestTinkoffBot"/>
      
      <ProjectLink 
          text="Minecraft launcher for Metro modpack"
          url="https://github.com/linuxfight/metro_launcher"/>
      
      <ProjectLink 
          text="A web application for the exchange of paper books"
          url="https://github.com/bookswapper"/>

      <ProjectLink
          text="Telegram bot for searching movies"
          url="https://github.com/linuxfight/MovieSearchBot"/>
    </div>
  </div>
</template>

<style scoped>
</style>
