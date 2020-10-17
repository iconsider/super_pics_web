<template>
  <div id="app">
    <HelloWorld msg="particles-bg-vue"/>
    <particles-bg type="fountain" :num="5" :bg="true"/>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import { ParticlesBg } from "particles-bg-vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    ParticlesBg
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
