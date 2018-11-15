<template>
  <div id="app">
    <h1>Word Search Toolset</h1>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
#app {
  font-family: 'Spicy Rice', cursive;
  /*font-family: 'Avenir', Helvetica, Arial, sans-serif;*/
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
  padding: 1rem 2rem;
}

h1{
  font-size: 60px;
  text-shadow: 2px 2px red;
  /*color: #1509ED;*/
}
</style>
