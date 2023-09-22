<template>
    <footer>
        <AppFooterTop></AppFooterTop>
        <AppFooterBottom></AppFooterBottom>
    </footer>
</template>

<script>
import AppFooterBottom from './AppFooterBottom.vue';
import AppFooterTop from './AppFooterTop.vue';


export default {
    name: 'AppFooter',
    components: { AppFooterTop, AppFooterBottom }
}
</script>

<style lang="scss" scoped>
@use '../assets/scss/partials/variabiles' as *;
</style>