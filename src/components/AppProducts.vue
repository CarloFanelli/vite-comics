<template>
    <div class="products_space position-relative">
        <div class="my_btn text-center btn_abs">
            <a href="#">
                <h6>Current series</h6>
            </a>
        </div>
        <div class="content d-flex">

            <div class="row">


                <AppProduct v-for="product in products" :thumb="product.thumb" :series="product.series" class="col-2">
                </AppProduct>

            </div>
        </div>
        <div class="row justify-content-center">
            <div class="col-2">

                <div class="my_btn text-center">
                    <a href="#">
                        <h6>load more</h6>
                    </a>
                </div>

            </div>
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

    .my_btn {

        margin-bottom: 3rem;
        background: $dc__evidence;
        padding: 0.5rem 1rem;

        h6 {
            color: $dc__light;
            text-transform: uppercase;
            margin: 0;
            font-weight: 700;
        }

        a {
            text-decoration: none;
        }
    }

    .btn_abs {
        position: absolute;
        top: -1rem;
        left: 13rem;
    }
}
</style>