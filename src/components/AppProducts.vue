<template>
    <div class="products_space">
        <div class="content d-flex">

            <AppProduct v-for="product in products" :thumb="product.thumb" :series="product.series"></AppProduct>

        </div>
    </div>
</template>

<script>

import products from '../products.js'
import AppProduct from './AppProduct.vue';

export default {

    name: 'AppProducts',

    data() {
        return {
            products
        }
    },
    components: {
        AppProduct
    }


}
</script>

<style lang="scss" scoped>
@use '../assets/scss/partials/variabiles' as *;

.products_space {

    background: $dc__dark;
    position: relative;
    z-index: 1;

    .content {
        max-width: 1140px;
        margin: 0 auto;
        padding: 2rem 0;
        text-align: center;
    }
}
</style>