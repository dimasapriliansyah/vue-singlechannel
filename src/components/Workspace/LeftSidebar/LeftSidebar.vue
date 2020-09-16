<template>
  <div class="sidebar-group">
    <workorder></workorder>
  </div>
</template>

<script>
import Workorder from "./Workorder";

export default {
  name: "LeftSidebar",
  components: {
    Workorder,
  },
};
</script>