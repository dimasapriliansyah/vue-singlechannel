<template>
  <div class="content">
    <left-sidebar></left-sidebar>
    <chat></chat>
    <tabs></tabs>
  </div>
</template>

<script>
import LeftSidebar from "./LeftSidebar/LeftSidebar";
import Chat from "../Shared/Chat/Chat";
import Tabs from "./Tabs/Tabs";

export default {
  name: "Workspace",
  components: {
    LeftSidebar,
    Chat,
    Tabs
  },
};
</script>