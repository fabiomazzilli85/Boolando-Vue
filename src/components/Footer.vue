<script>
export default {
  created() {
    console.log('Componente footer creato.');
    // Essendo questo componente un footer, non saprei che script eseguire seS non un banalissimo console.log.
  }
}
</script>

<template>
<footer>
    <div class="footer container background_footer">
        <div class="text">
            <h3 class="bottom_footer">Boolando Srl</h3>
            <div class="footer_flex footer-color">
                <div>Informazioni legali</div>
                <div>Informazioni sulla Privacy</div>
                <div>Diritto di Recesso</div>
                <img class="logo" src="/boolean-logo.png" alt="">
            </div>
        </div>
    </div>
</footer>
</template>

<style>
h3 {
    text-align: center;
    padding-top: 15px;
    color: white;
    margin: 10px 0;
}

.logo {
    display: block;
    width: 75px;
}

footer {
    margin-top: 50px;
    font-family: Arial, Helvetica, sans-serif;
    text-transform: uppercase;
}

.background_footer {
    background-color: #1F2544;
    color: white;
    width: 100%;

}

.footer_flex {
    display: flex;
    justify-content: space-between;
    gap: 20px;
    padding: 20px;
} 

.footer-color {
    color: white;
}
</style>