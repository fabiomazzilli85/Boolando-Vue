<script>

</script>

<template>
     <main>
        <div class="container">
            <div class="row">

            <!-- Inizio Foto Modello 1 -->
                
                <div class="image_card section_margin">
                    <div class="image_position">
                        <img class="image_size image_first" src="/1.webp" alt="Foto Modello Levi's">
                        <img class="image_size image_second" src="/1b.webp" alt="Foto Modello Levi's">
                        <div class="sconto">-50%</div>
                        <div class="sostenibilità">Sostenibilità</div>
                        <div class="heart">&hearts;</div>
                    </div>
                    
                    <div>Levi's</div>
                    <h2>RELAXED FIT TEE UNISEX</h2>
                    <span class="price">14.99 &euro;</span> 
                    <span class="old_price">24.99 &euro;</span>
                </div>

            <!-- Fine Foto Modello 1 -->
             <!-- Inizio Foto Modello 2 -->

             <div class="image_card section_margin">
                    <div class="image_position">
                        <img class="image_size image_first" src="/2.webp" alt="Foto Modella Guess">
                        <img class="image_size image_second" src="/2b.webp" alt="Foto Modella Guess">
                        <div class="sconto">-30%</div>
                        <div class="heart">&hearts;</div>
                    </div>
                    
                    <div>Guess</div>
                    <h2>Roses Tee</h2>
                    <span class="price">20.99  &euro;</span> 
                    <span class="old_price">29.99 &euro;</span>
                </div>

                <!-- Fine Foto Modello 2 -->

                <!-- Inizio Foto Modello 3 -->

                 <div class="image_card section_margin">
                    <div class="image_position">
                        <img class="image_size image_first" src="/3.webp" alt="Foto Modello Levi's">
                        <img class="image_size image_second" src="/3b.webp" alt="Foto Mdello Levi's">
                        <div class="sconto">-50%</div>
                        <div class="sostenibilità">Sostenibilità</div>
                        <div class="heart">&hearts;</div>
                    </div>
                    
                    <div>Come zucchero filato</div>
                    <h2>Voglia di colori pastello</h2>
                    <span class="price">129.99 &euro;</span> 
                    <span class="old_price">184.99 &euro;</span>
                </div>

                <!-- Fine Foto Modello 3 -->

                <!-- Inizio Foto Modello 4 -->

                 <div class="image_card section_margin">
                    <div class="image_position">
                        <img class="image_size image_first" src="/4.webp" alt="Foto Modello Levi's">
                        <img class="image_size image_second" src="/4b.webp" alt="Foto Modello">
                        <div class="sconto">-50%</div>
                        <div class="sostenibilità">Sostenibilità</div>
                        <div class="heart">&hearts;</div>
                    </div>
                    
                    <div>Levi's</div>
                    <h2>TEE UNISEX</h2>
                    <span class="price">14.99 &euro;</span> 
                    <span class="old_price">29.99 &euro;</span>
                </div>

                <!-- Fine modello 4 -->
                
                <!-- Inizio modello 5 -->

                <div class="image_card section_margin">
                    <div class="image_position">
                        <img class="image_size image_first" src="/5.webp" alt="Foto Modello Levi's">
                        <img class="image_size image_second" src="/5b.webp" alt="Foto Modello Levi's">
                        <div class="heart">&hearts;</div>
                    </div>
                    
                    <div>Maya deluxe</div>
                    <h2>Stripe Bodice</h2>
                    <span class="price">99.99 &euro;</span>
                </div>

                <!-- Fine modello 5 -->

                <!-- Inizio Modello 6 -->

                <div class="image_card section_margin">
                    <div class="image_position">
                        <img class="image_size image_first" src="/6.webp" alt="Foto Modello Levi's">
                        <img class="image_size image_second" src="/6b.webp" alt="Foto">
                        <div class="sostenibilità_no_margin">Sostenibilità</div>
                        <div class="heart">&hearts;</div>
                    </div>
                    
                    <div>Esprit</div>
                    <h2>Maglione Black</h2>
                    <span class="price">29.99 &euro;</span> 
                </div>

                <!-- Fine modello 6 -->
        </div>
    </div>
    </main>
</template>

<style>
    .image_position {
    position: relative;
}

.image_card .image_second {
    display: none;
}

.image_card:hover .image_second {
    display: block;
}
.image_card:hover .image_first {
    display: none;
}

.sconto {
    position: absolute;
    bottom: 20px;
    background-color: red;
    color: white;
    padding: 5px;
    border-radius: 4px;
}

.sostenibilità {
    position: absolute;
    left: 60px;
    bottom: 20px;
    background-color: green;
    color: white;
    padding: 5px;
    border-radius: 4px;
}

.heart {
    position: absolute;
    top: 10px;
    right: 0px;
    background-color: white;
    color: black;
    width: 30px;
    height: 30px;
    text-align: center;
    padding: 7px;
} 

.sostenibilità_no_margin  {
    position: absolute;
    bottom: 20px;
    background-color: green;
    color: white;
    padding: 3px 7px;
}

.image_size {
    width: 300px;
}

.price {
    color: red;
}

.old_price {
    color: grey;
    text-decoration:line-through;
}

.section_margin {
    margin: 20px 20px;
}

.heart:hover {
    color: red;
}
</style>