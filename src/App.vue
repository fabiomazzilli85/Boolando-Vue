<template>
  <Navbar />
  <Main />
  <Footer />
</template>

<script>
import Navbar from './components/Navbar.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';

export default {
  // Registro il componente.
  components: {
    Navbar,
    Main,
    Footer,
  },
  data() {
    return {}
  }
}
</script>

<style lang="scss">
/* Stili CSS */
@use './style/general';
</style>
