<script setup>
import {  RouterView } from 'vue-router'
import NavBar from './components/NavBar.vue';
import FooterComponents from './components/FooterComponents.vue'
</script>

<template>
  <div class="container">
    <header>
      <NavBar />
    </header>
  </div>
  <RouterView />

  <div class="">
    <footer>
      <FooterComponents />
    </footer>
  </div>
</template>

<style scoped>
  
</style>
