<template>
  <div id="app">
    <Navbar />
    <img alt="Vue LOGO" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js APP"/>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'App',
  components: {
    Navbar,
    HelloWorld,
  },
};
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
