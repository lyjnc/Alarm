<template>
  <div id="app">
    <!--<Login></Login>-->
    <router-view></router-view>
  </div>
</template>

<script>
// import Login from './components/pages/login'

export default {
  name: 'app',
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /*margin-top: 60px;*/
}
</style>
