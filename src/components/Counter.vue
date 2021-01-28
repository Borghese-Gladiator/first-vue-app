<template>
  <div id="counter">Counter (counts up every second): {{ counter }}</div>
</template>

<script>
export default {
  name: "Counter",
  data() {
    return {
      counter: 0
    }
  },
  mounted() {
    setInterval(() => {
      this.counter++
    }, 1000)
  }
};
</script>