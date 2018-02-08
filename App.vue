<template>
  <div id="app">
    <draw/>
  </div>
</template>

<script>
import draw from './components/Draw'

export default {
  name: 'App',
  components: {
    draw
  }
}
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: #ddd;
}
</style>
