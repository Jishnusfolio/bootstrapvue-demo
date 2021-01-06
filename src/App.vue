<template>
  <div id="app">
    <Navbar />
    <img class="logo" alt="Vue logo" src="./assets/j-logo.png">
    <HelloWorld msg="Jishnu's API App"/>
    <Cards />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Navbar from './components/Navbar.vue'
import Cards from './components/Cards.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Navbar,
    Cards
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
}

.logo{
  width: 200px;
  height: 200px;
}
</style>
