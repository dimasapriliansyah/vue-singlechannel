<template>
  <div class="chat">
    <chat-header></chat-header>
    <chat-body></chat-body>
    <chat-footer></chat-footer>
  </div>
</template>

<script>
import ChatHeader from "./ChatHeader";
import ChatBody from "./ChatBody";
import ChatFooter from "./ChatFooter";
export default {
  name: "Chat",
  components: {
    ChatHeader,
    ChatBody,
    ChatFooter,
  },
};
</script>