<script setup>
import {  RouterView } from 'vue-router'
import NavBar from './components/NavBar.vue';
</script>

<template>
  <div class="container">
    <header>
      <NavBar />
    </header>

    
    <RouterView />
  </div>
</template>

<style scoped>
  
</style>
