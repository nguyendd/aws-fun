<template>
  <div id="app">
    <!--
    <img alt="Vue logo" src="./assets/logo.png">
    -->
    <Quadrant favorite-color="blue"/>
  </div>
</template>

<script>

import Quadrant from './components/Quadrant.vue'

export default {
  name: 'app',
  components: {
    Quadrant
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
