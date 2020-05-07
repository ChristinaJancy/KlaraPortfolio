<template>
<v-app>
  <Home app class="white" light />
  </v-app>
</template>

<script>
import Home from './views/Home.vue'

export default {
  name: 'App',
  components: {
    Home
  }
}
</script>

<style>
#app {
  font-family: Chalkduster, Helvetica, sans-serif;
}
</style>
