<template>
  <div>
    <div id="app">
      <img alt="Vue logo" src="./assets/logo.png">
      <HelloWorld msg="Welcome to Your Vue.js App"/>
      <Dashboard></Dashboard>
    </div>
    <div>
      <Footer></Footer>
    </div>
  </div>
    
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Dashboard from './components/Dashboard.vue'
import Footer from './components/Footer'

export default {
  name: 'app',
  components: {
    HelloWorld,
    Dashboard,
    Footer
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
