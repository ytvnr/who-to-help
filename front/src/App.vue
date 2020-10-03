<template>
  <Header />
  <Body />
</template>

<script>
import Header from './components/Header.vue';
import Body from './components/Body.vue';

export default {
  name: 'Who to help',
  components: {
    Header,
    Body,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
