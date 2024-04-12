<script>
export default {
    props: ['product'],
    methods: {
        getStaticPath(fileName) {
            return '/' + fileName;
        }
    }
}
</script>

<template>
    <div class="image_card section_margin">
        <div class="image_position">
            <img class="image_size image_first" :src="getStaticPath(product.frontImage)" alt="Foto Modello Levi's">
            <img class="image_size image_second" :src="`/${product.backImage}`" alt="Foto Modello Levi's">
            <div class="sconto">-50%</div>
            <div class="sostenibilità">Sostenibilità</div>
            <div class="heart">&hearts;</div>
        </div>

        <div>{{ product.brand }}</div>
        <h2>{{ product.title }}</h2>
        <span class="price">{{ product.price }}</span>
        <span class="old_price">24.99 &euro;</span>
    </div>
</template>

<style lang="scss" scoped>
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

.sostenibilità_no_margin {
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
    text-decoration: line-through;
}

.section_margin {
    margin: 20px 20px;
}

.heart:hover {
    color: red;
}
</style>