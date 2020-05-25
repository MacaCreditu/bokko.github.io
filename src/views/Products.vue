<template>
  <div id="app">
    <img class="logo" alt="Bokko logo" src="./assets/logo-bokko.jpg">
    <HelloWorld msg="Winter Collection"/>
    <PrimaryNav></PrimaryNav>
    <h1>Products {{ category }}</h1>
  </div>
</template>

<script>
import PrimaryNav from './components/PrimaryNav.vue'
import HelloWorld from './components/HelloWorld.vue'


export default {
  name: 'App',
  components: {
    PrimaryNav
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
.logo{
  width: 100%;
  max-width: 700px;
}
</style>
