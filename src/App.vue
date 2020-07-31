<template>
  <div id="app">
<Menu></Menu>
    <info/>

  </div>
</template>

<script>
import Menu from "./components/Menu";
import Info from "./components/Info";
export default {
  name: 'App',
  components: {
    Menu,
    Info,
  }
}
</script>

<style>
/*#app {*/
/*  font-family: 'Avenir', Helvetica, Arial, sans-serif;*/
/*  -webkit-font-smoothing: antialiased;*/
/*  -moz-osx-font-smoothing: grayscale;*/
/*  text-align: center;*/
/*  color: #2c3e50;*/
/*  margin-top: 60px;*/
/*}*/
</style>
