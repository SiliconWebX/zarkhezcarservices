<template>
  <div id="app">
    <img
      alt="Zarkhez Car Services Ahmedabad"
      src="./assets/logo.png"
      width="25%"
    />
    <zarkhez msg="Zarkhez Car Services" />
  </div>
</template>

<script>
import zarkhez from "./components/zarkhez.vue";

export default {
  name: "App",
  components: {
    zarkhez,
  },
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 10px;
}
</style>
