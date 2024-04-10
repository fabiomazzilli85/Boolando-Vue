<script>
export default {
  created() {
    console.log('Componente navbar creato.');
    // Essendo questo componente una navbar, non saprei che script eseguire se non un banalissimo console.log.
  }
}
</script>

<template>
     <nav class="container">
            <div class="row">
            <ul class="main_nav">
                <li>
                    <a href="#">Donna</a>
                </li>
                <li>
                    <a href="#">Uomo</a>
                </li>
                <li>
                    <a href="#">Bambino</a>
                </li>
            </ul>
            </div>
            <img class="logo" src="/boolean-logo.png" alt="">
        </nav>
</template>

<style lang="scss">
    li {
        list-style: none;
    a  {text-decoration: none;
        color: white;
        text-transform: uppercase;}  
    }

    .main_nav {
        background-color: #8CB9BD;
    }
</style>