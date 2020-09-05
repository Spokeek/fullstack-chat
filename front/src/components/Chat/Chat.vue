<script>
import Discussion from "./components/Discussion";
import Input from "./components/Input";

export default {
  components: {
    Discussion,
    Input,
  },
};
</script>

<template>
  <div>
    <div id="discussion">
      <Discussion />
    </div>
    <div id="input">
      <Input />
    </div>
  </div>
</template>

<style scoped>
#discussion {
  height: 80%;
}
#input {
  height: cal(20% - 50px);
  margin-top: 50px;
}
</style>