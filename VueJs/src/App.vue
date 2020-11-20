<template>
  <div id="app">
    <img src="./assets/logo.png">
    <h1>{{msg}}</h1>
    <counter></counter>
    <counter></counter>
    <counter></counter>
    <counter></counter>
    <counter></counter>
  </div>
</template>

<script>
import Counter from './Counter.vue'

export default {
  components: {Counter},
  data() {
    return {
      msg: 'Hello Vue'
    }
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
