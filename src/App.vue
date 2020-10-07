<template>
  <div id="app">
    <GitCat msg="Git Cat"/>
  </div>
</template>

<script>
import GitCat from './components/GitCat.vue'

export default {
  name: 'App',
  components: {
    GitCat,
  },
};
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

body {
  background-color: rgb(57, 204, 214);
}
</style>
