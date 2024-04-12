<template>
  <Navbar />
  <Main />
  <Card />
  <Footer />
</template>

<script>
import Navbar from './components/Navbar.vue';
import Main from './components/Main.vue';
import Card from './components/Card.vue';
import Footer from './components/Footer.vue';

export default {
  // Registro il componente.
  components: {
    Navbar,
    Main,
    Card,
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
