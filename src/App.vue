<script>

import AppHeader from './components/AppHeader.vue';
import AppIconSpace from './components/AppIconSpace.vue';
import Appfooter from './components/appfooter.vue';

import icons from './icons'

export default {

  data() {

    return {
      icons,

    }
  },
  components: {
    AppHeader,
    AppIconSpace,
    Appfooter
  }
}
</script>

<template>
  <AppHeader></AppHeader>

  <main>
    <div class="bg-dark p-5">
      <h1 class="text-white">some content</h1>
    </div>

    <AppIconSpace v-for="icon in icons" :img="icon.img" :title="icon.title"></AppIconSpace>

  </main>

  <Appfooter></Appfooter>
</template>

<style></style>
