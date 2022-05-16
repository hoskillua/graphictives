<template>
  <div>
    <Navbar />
    <RouterView />
  </div>
</template>

<script>
import Navbar from './components/partials/Navbar.vue';
import {RouterView} from 'vue-router';
export default {
  name: 'App',
  components: {
    Navbar,
    RouterView,
  }
}
</script>

<style>
@import '@/styles/compiled.css';
</style>
