<template>
  <div id="hit-counter" class="demo">
    <p>Counter: {{ counter }}</p>
    <button v-on:click="increaseCount">Increase Count</button>
  </div>
</template>

<script>
export default {
  name: "HitCounter",
  data() {
    return {
      counter: 0,
    };
  },
  methods: {
    increaseCount() {
      this.counter = this.counter + 1;
    },
  },
};
</script>

<style scoped>
.demo {
  font-family: sans-serif;
  border: 1px solid #eee;
  border-radius: 2px;
  padding: 20px 30px;
  margin-top: 1em;
  margin-bottom: 40px;
  user-select: none;
  overflow-x: auto;
}
</style>