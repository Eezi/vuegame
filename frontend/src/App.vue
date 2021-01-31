<template>
  <div id="app">
    <BlockGame />
  </div>
</template>

<script>
import BlockGame from './components/BlockGame.vue'

export default {
  name: 'App',
  components: {
    BlockGame 
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
  background: #ddd;
  height: 100vh;
}
</style>
