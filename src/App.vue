<template>
  <div id="app">
    <img alt="Moeda Logo" src="./assets/logo-moeda.png" class="logotipo">
    <Login></Login>
  </div>
</template>

<script>
import Login from "./components/Login";

export default {
  name: 'App',
  components: {
    Login
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
    background-color: #2c3e50;
    height: 627px;
  }

  .logotipo {
    height: 250px;
  }

</style>
