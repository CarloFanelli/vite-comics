<script>

import AppFooter from './AppFooter.vue';
import AppHeader from './components/AppHeader.vue';
import AppIconSpace from './components/AppIconSpace.vue';
import HelloWorld from './components/HelloWorld.vue'

export default {

  data() {

    return {

    }
  },
  components: {
    AppHeader,
    AppIconSpace,
    AppFooter
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
  <AppFooter></AppFooter>
</template>

<style scoped></style>
