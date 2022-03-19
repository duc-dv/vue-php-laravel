<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <HelloDuc /> 
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import HelloDuc from './views/components/HelloDuc.vue'
export default {
  name: 'App',
  components: {
    HelloDuc
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
