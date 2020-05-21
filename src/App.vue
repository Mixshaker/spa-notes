<template>
  <div id="app" class="container">
    <img src="./assets/logo.png" class="logo">
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
  text-align: center;
  color: #2c3e50;
  margin-top: 40px;
}

.logo{
  box-sizing: border-box;
  width: 80px;
}

.container{
  max-width: 1200px;
  margin: 0 auto;
}
</style>
