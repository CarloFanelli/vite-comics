<template>
    <div class="single_product">
        <img :src="thumb" alt="">
        <p>{{ series }}</p>

    </div>
</template>

<script>
export default {
    name: 'AppProduct',

    props: {
        thumb: String,
        price: String,
        series: String,
        type: String,
    }

}
</script>

<style lang="scss" scoped>
@use '../assets/scss/partials/variabiles' as *;

.single_product {
    display: flex;
    flex-direction: column;
    margin: 1rem 0;

    p {
        color: $dc__light;
        text-align: left;
        text-transform: uppercase;
    }

    img {
        max-width: 100%;
        object-fit: cover;
        aspect-ratio: 1;
    }

}
</style>