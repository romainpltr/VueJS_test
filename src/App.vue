<template>
  <div id="app">
    <img src="./assets/logo.png">
    <Cars name='ford' model='fiesta' year='2008'></Cars>
    <router-view/>
  </div>
</template>

<script>
import CarPage from './pages/CarPage'
export default {
  name: 'App',
  components: {
    CarPage
  }
}
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
