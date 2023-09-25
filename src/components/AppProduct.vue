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
    p {
        color: $dc__light;
    }
}
</style>