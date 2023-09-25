<script>

import AppFooter from './components/AppFooter.vue';
import AppHeader from './components/AppHeader.vue';
import AppIconSpace from './components/AppIconSpace.vue';
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
    AppProducts
  }
}
</script>

<template>
  <AppHeader></AppHeader>

  <main>
    <div class="bg-dark p-5">
      <h1 class="text-white">some content</h1>
    </div>
    <AppProducts></AppProducts>

    <AppIconSpace></AppIconSpace>

    <AppFooter></AppFooter>

  </main>
</template>

<style></style>
