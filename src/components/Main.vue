<script>
import Card from './Card.vue';
import data from '../assets/db.json';

export default {
    components: {
        Card
    },
    data() {
        return {
            products: data.products
        }
    },
}
</script>

<template>
    <main>
        <div class="container">
            <div class="row">
                <div v-for="element in products" :key="element.id" class="col-12 col-md-6 col-lg-4">
                    <Card :product="element" />
                </div>
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