<template>
  <v-app>
    <v-app-bar app>
      <h2>Demo</h2>
    </v-app-bar>
    <v-main app>
      <HelloWorld msg="Welcome to Your Vue.js App"/>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>

</style>
