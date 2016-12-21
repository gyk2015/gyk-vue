<template>
  <div id="app">
    <img src="./assets/logo.png">
    <hello></hello>
    <top></top>
  </div>
    
</template>

<script>
import Hello from './components/Hello'
import Top from './components/Top'
export default {
  name: 'app',
  components: {
    Hello,
    Top
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
