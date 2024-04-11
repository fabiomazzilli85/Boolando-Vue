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
                <img class="logo" src="/boolean-logo.png" alt="">
            </ul>
            </div>
        </nav>
</template>

<style lang="scss" scoped>
@use '../style/partial/layout';

li {
    list-style: none;
a  {text-decoration: none;
    color: white;
    font-family: Arial, Helvetica, sans-serif;
    text-transform: uppercase;}  
.logo {
    width: 75px;
    display: block;
    align-items: center;}
}

.main_nav {
    background-color: #8CB9BD;
    width: 100%;
    display: flex;
    align-items: center;
    gap: 20px;
    padding: 25px;
    margin-bottom: 50px;
}
</style>