<template>
  <div id="app">
    <AA></AA>
    <BB></BB>
  </div>
</template>

<script>
import AA from './components/A';
import BB from './components/B';

export default {
  name: 'app',
  components: {
    AA,
    BB,
  },
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
