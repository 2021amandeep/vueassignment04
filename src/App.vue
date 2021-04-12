<template>
  <div id="app">
    <h1><Assignment/></h1>
    <Styleandclass/>

  </div>
</template>

<script>

import Assignment from './components/Assignment.vue'
import Styleandclass from './components/Styleandclass.vue'


export default {
  name: 'App',
  components: {
    Assignment,
    Styleandclass
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
