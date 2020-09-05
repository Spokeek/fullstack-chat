<script>
export default {
  data: () => ({
    text: "",
  }),
  methods: {
    submit() {},
  },
};
</script>

<template>
  <div>
    <input v-model="text" />
    <button>Submit</button>
  </div>
</template>

<style scoped>
</style>