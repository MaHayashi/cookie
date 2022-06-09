<template>
  <div id="app"> <!-- Sempre com DIV-->
    <img alt="Cookie" src="./assets/cookie.jpeg">
    <HelloCookie msg="Cookie"/>
    <WannaCookie></WannaCookie>
  </div> 
</template>

<script>
import HelloCookie from './components/HelloCookie.vue'
import WannaCookie from './components/WannaCookie.vue'

export default {
  name: 'App',
  components: {
    HelloCookie, WannaCookie
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
