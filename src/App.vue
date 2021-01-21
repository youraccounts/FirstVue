<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  
  <HelloWorld title="IS" msg="Dear Seakthong.Queen.Vue.js  " />
  <!-- <FirstVue msg="Dec 22, 2020" /> -->
  <!-- <FirstVue msg="MY WORLD IN MY HEAD" /> -->
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
// import FirstVue from "./components/first.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    // FirstVue,
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
