<template>
  <div><flow-panel></flow-panel></div>
</template>

<script>
import FlowPanel from "@/components/flow/Panel";

export default {
  name: "App",
  components: {
    FlowPanel
  }
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
