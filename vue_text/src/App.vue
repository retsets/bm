<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>

import Login from './components/Login.vue'


export default {
  name: 'App',
  components: {
    Login
  }
}
</script>

<style>
html,body{
  width: 100%;
  height: 100%;
}
#app {
  width: 100%;
  height: 100%;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
