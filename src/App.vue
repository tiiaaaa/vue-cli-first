<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <VueTitle/>
  </div>
</template>

<script>
import VueTitle from './components/VueTitle.vue'

export default {
  name: 'App',
  components: {
    VueTitle
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
