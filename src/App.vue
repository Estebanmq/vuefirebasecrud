<template>
  <div id="app">
    <CRUDFirebase />
  </div>
</template>

<script>
import CRUDFirebase from './components/CRUDFirebase.vue';

export default {
  name: 'App',
  components: {
    CRUDFirebase
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
