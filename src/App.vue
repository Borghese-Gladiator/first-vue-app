<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <Counter />
  <HoverLabel />
  <HitCounter />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Counter from './components/Counter.vue';
import HoverLabel from './components/HoverLabel.vue';
import HitCounter from './components/HitCounter.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    Counter,
    HoverLabel,
    HitCounter
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
