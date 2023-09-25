<template>
    <div class="icon_space ">
        <div class="content d-flex">

            <AppIcon v-for="icon in icons" :img="icon.img" :text="icon.text"></AppIcon>
        </div>
    </div>
</template>

<script>
import icons from '../icons.js';
import AppIcon from './AppIcon.vue';

export default {
    name: 'AppIconSpace',

    data() {
        return {
            icons
        }
    },
    components: {
        AppIcon
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
        max-width: 1140px;
        margin: 0 auto;
        padding: 2rem 0;
        text-align: center;
    }


}
</style>