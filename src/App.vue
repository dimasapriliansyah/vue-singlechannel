<template>
  <div class="layout">
    <navigation></navigation>
    <workspace></workspace>
  </div>
</template>

<script>
import Navigation from "./components/Navigation.vue";
import Workspace from "./components/Workspace/Workspace.vue";

export default {
  name: "App",
  components: {
    Navigation,
    Workspace
  },
};
</script>

<style>
</style>
