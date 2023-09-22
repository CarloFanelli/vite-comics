<template>
    <div>
        <div class="icon_space">
            <div class="content d-flex justify-content-evenly align-items-center">
                <div class="col icon_text d-flex justify-content-center align-items-center">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                    <p class="text-uppercase">digital comics</p>
                </div>
                <div class="col icon_text d-flex justify-content-center align-items-center">
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                    <p class="text-uppercase">dc merchandise</p>
                </div>
                <div class="col icon_text d-flex justify-content-center align-items-center">
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                    <p class="text-uppercase">subscription</p>
                </div>
                <div class="col icon_text d-flex justify-content-center align-items-center">
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                    <p class="text-uppercase">comics shop locator</p>
                </div>
                <div class="col icon_text d-flex justify-content-center align-items-center">
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                    <p class="text-uppercase">dc power visa</p>


                    <!-- <div v-for="icon in services" class="col icon_text d-flex justify-content-center align-items-center">
                        <img :src="icon.img" alt="">
                        <p class="text-uppercase">{{ icon.text }}</p>
                    </div> -->

                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

    name: 'AppIconSpace',

    data() {
        return {
            services: [
                {
                    img: '../assets/img/buy-comics-digital-comics.png',
                    text: 'digital comics'
                },
                {
                    img: '../assets/img/buy-comics-comics-merchandise.png',
                    text: 'comics merchandise'
                },
                {
                    img: '../assets/img/buy-comics-subscription.png',
                    text: 'subscriptions'
                },
                {
                    img: '../assets/img/buy-comics-shop-locator.png',
                    text: 'comics shop-locator'
                },
                {
                    img: '../assets/img/buy-dc-power-visa.png',
                    text: 'dc power visa'
                },

            ]
        }
    }
}
</script>

<style lang="scss" scoped>
@use '../assets/scss/partials/variabiles' as *;

.icon_space {

    background: $dc__evidence;
    position: relative;
    z-index: 1;

    .content {
        color: $dc__light;
        max-width: 1140px;
        margin: 0 auto;
        padding: 2rem 0;
        text-align: center;
    }

    .icon_text {

        & img {


            max-width: 3rem;
            max-height: 3rem;
            margin-right: 0.3rem;
        }

        & p {
            font-size: 0.8rem;
            margin: 0;
        }

    }

}
</style>