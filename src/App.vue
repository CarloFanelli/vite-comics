<script>

import AppFooter from './components/AppFooter.vue';
import AppHeader from './components/AppHeader.vue';
import AppIconSpace from './components/AppIconSpace.vue';
import AppJumbo from './components/AppJumbo.vue';
import AppProducts from './components/AppProducts.vue';


export default {

  data() {

    return {

    }
  },
  components: {
    AppHeader,
    AppIconSpace,
    AppFooter,
    AppProducts,
    AppJumbo
  }
}
</script>

<template>
  <AppHeader></AppHeader>

  <main>
    <AppJumbo></AppJumbo>
    <AppProducts></AppProducts>

    <AppIconSpace></AppIconSpace>

    <AppFooter></AppFooter>

  </main>
</template>

<style></style>
