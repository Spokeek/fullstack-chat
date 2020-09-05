<script>
import Chat from "./components/Chat";

export default {
  name: "App",
  components: {
    Chat,
  },
};
</script>

<template>
  <div id="app" class="width-100 height-100">
    <Chat id="chat" />
  </div>
</template>

<style>
#app {
  background-color: #fad390;
}

#chat {
  max-width: 400px;
  margin: auto;
}
</style>
