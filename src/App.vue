<script>

import AppHeader from './components/AppHeader.vue';
import AppIconSpace from './components/AppIconSpace.vue';
import Appfooter from './components/appfooter.vue';


export default {

  data() {

    return {

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

    <AppIconSpace></AppIconSpace>

  </main>

  <Appfooter></Appfooter>
</template>

<style></style>
