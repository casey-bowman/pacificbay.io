<template>
  <div id="app">

    <!--<a href="http://umunhum.io:8877">-->
    <a href="https://github.com/rust-flavored-bitcoin/umunhum">
      <img src="./assets/umunhum.jpg" height="169" width="300"/><br/>
      Mount Umunuhum Project
    </a>
    <br/>
    <br/>

    <a href="http://losgatos.io:8888">
      <img src="./assets/losgatos.jpeg" height="169" width="300"/><br/>
      Los Gatos Reading Group
    </a>
    <div><Welcome/></div>

  </div>

</template>

<script>
import Welcome from './components/Welcome'

export default {
  name: 'App',
  components: {
    Welcome
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
