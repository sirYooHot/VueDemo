<template>
  <div id="app">
    <img class="appImg" src="./assets/logo.png">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.appImg {
  display: block;
  margin: 60px auto 0;
  color: #2c3e50;
}
</style>
