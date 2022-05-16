<template>
  <div class="nav">
      <Logo />
  </div>
</template>

<script>
import Logo from '../icons/Logo.vue';

export default {
  name: 'Navbar',
  components: {
    Logo
  }
}
</script>

<style>
.nav{
    display: flex;
    width: 100%;
    justify-content: center;
    align-items: center;
    height: 100px;
    background-color: black;
}
</style>