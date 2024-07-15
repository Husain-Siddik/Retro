<script setup>
import Navber from './components/Navber.vue';

</script>

<template>
  <div class="">
    <header class="">
      <Navber />

    </header>

    <div class=" container mx-auto">
      <RouterView />
    </div>
  </div>
</template>

<style scoped></style>
