<script setup>
import AppHeader from './components/AppHeader.vue';
import AppFooter from './components/AppFooter.vue';
import AppNavbar from './components/AppNavbar.vue';

</script>

<template>
  <AppHeader/>
  <AppNavbar/>
  <RouterView/>
  <AppFooter/>
</template>

<style scoped>

</style>
