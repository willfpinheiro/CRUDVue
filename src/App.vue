<template>
  <div id="app">
  <Cabecalho></Cabecalho>
  </div>
</template>

<script>
import Cabecalho from './components/Cabecalho'

export default {
  name: 'App',
  components: {
    Cabecalho
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
