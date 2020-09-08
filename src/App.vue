<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/Felipe.jpg">
    <HelloWorld msg="O Felipe é muito muito bom"/>
  </div>
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
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

#app img {
    max-width:200px;
    max-height:150px;
    width: auto;
    height: auto;
}
</style>
