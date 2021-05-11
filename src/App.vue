<template>
  <div id="app">
    <<<<<<< HEAD
    <Box />
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    =======
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <Img />
    >>>>>>> b
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Box from "./components/Box";
import Img from "./components/Img";

export default {
  name: "App",
  components: {
    HelloWorld,
    Box,
    Img,
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
