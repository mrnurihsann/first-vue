<template>
  <div id="app">
    <first />
  </div>
</template>

<script>
import first from './components/first.vue'

export default {
  name: 'App',
  components: {
    first
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
