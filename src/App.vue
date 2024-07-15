<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Navber from './components/Navber.vue';
import Herocom from './components/Herocom.vue';
</script>

<template>
  <header class=" container mx-auto">
    <!-- Navber Start -->
    <Navber />
    <!-- Navber End -->
    <Herocom />
    <nav>
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/about">About</RouterLink>
    </nav>

  </header>

  <RouterView />
</template>

<style scoped></style>
