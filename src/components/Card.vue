<template>
    
    <grid>
        <img v-bind:src="url" :alt="nombre" alt="descripcion, precio">
        <h4>{{ nombre }}</h4>
        <p> {{ descripcion }}</p>
        <h5> {{ precio }}</h5>
    </grid>
</template>

<script>
import Grid from "./Grid.vue";
    export default {
    props: {
        url: { String, },
        nombre: { String, },
        descripcion: { String, },
        precio: { String, },
    },
    components: { Grid }
};
</script>

<style scoped>
    img {
        width: 11rem;
        height: 11rem;
        padding: 0.2rem;
        background-color: snow;

    }
    a {
        text-decoration: none;
        color:snow;
        background: #301675;
        padding: 0.2rem;
        border-radius: 5px;
        border: 1px solid #f2f2f2;
    }
</style>