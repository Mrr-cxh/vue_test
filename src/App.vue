<template>
  <div id="app">
    <Box />
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <Img />
    <Nav />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Box from "./components/Box";
import Img from "./components/Img";
import Nav from "./components/Img";

export default {
  name: "App",
  components: {
    HelloWorld,
    Box,
    Img,
    Nav,
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
