<template>
  <Navbar />
</template>

<script>
import Navbar from './components/Navbar.vue';

export default {
  // Registro il componente.
  components: {
    Navbar
  },
  data() {
    return {}
  }
}
</script>

<style lang="scss">
/* Stili CSS */
@use '/style/general';
</style>
