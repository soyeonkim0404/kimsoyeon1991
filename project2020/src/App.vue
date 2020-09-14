<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <myHeader />
    <myContent msg="Welcome to Your Vue.js App"/>
    <myFooter />
  </div>
</template>

<script>
import myHeader from './components/myHeader.vue'
import myContent from './components/myContent.vue'
import myFooter from './components/myFooter.vue'

export default {
  name: 'App',
  components: {
    myHeader,
    myContent,
    myFooter
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
  margin-top: 60px;
}
</style>
