<template>
  <div id="app">
  
    <Demo/> 
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Demo from './components/Demo12.vue'
export default {
  name: 'App',
  components: {
    HelloWorld,Demo
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
.demo1{
  width: 200px;
  height: 200px;
  background-color: yellow;
}
</style>
