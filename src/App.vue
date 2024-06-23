<script setup>
import {  RouterView } from 'vue-router'
import NavBar from './components/NavBar.vue';
</script>

<template>
  <div class="container">
    <header>
      <NavBar />
    </header>
  </div>
  <RouterView />
</template>

<style scoped>
  
</style>
