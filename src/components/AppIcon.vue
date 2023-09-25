<template>
    <div class="col icon_text d-flex justify-content-center align-items-center">
        <img :src="getUrlImg(img)" alt="">
        <p class="text-uppercase">{{ text }}</p>

    </div>
</template>

<script>
export default {
    name: 'AppIcon',

    props: {
        img: String,
        text: String
    },
    methods: {
        getUrlImg(img) {
            return new URL(img, import.meta.url).href
        }
    },


}
</script>

<style lang="scss" scoped>
@use '../assets/scss/partials/variabiles' as *;

.icon_text {

    img {


        max-width: 3rem;
        max-height: 3rem;
        margin-right: 0.3rem;
    }

    p {
        color: $dc__light;
        font-size: 0.8rem;
        margin: 0;
    }
}
</style>