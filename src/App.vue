<template>
  <Checker />
</template>

<script lang="ts">
  import { defineComponent } from "vue";
  import Checker from "./components/Checker.vue";

  export default defineComponent({
    name: "App",
    components: {
      Checker,
    },
  });
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
