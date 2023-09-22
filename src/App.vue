<script>

import AppHeader from './components/AppHeader.vue';
import HelloWorld from './components/HelloWorld.vue'

export default {

  data() {

    return {

    }
  },
  components: {
    AppHeader,
  }
}
</script>

<template>
  <AppHeader></AppHeader>

  <main>
    <div class="bg-dark p-5">
      <h1 class="text-white">some content</h1>
    </div>
  </main>

  <footer>

  </footer>
</template>

<style scoped></style>
