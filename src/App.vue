<template>
  <div id="app">
    <Jumbotron></Jumbotron>
    <img alt="Vue logo" src="./assets/logo.png">
    <Title></Title>
  </div>
</template>

<script>
import Title from './components/Title.vue'
import Jumbotron from './components/Jumbotron.vue'

export default {
  name: 'App',
  components: {
    Title,
    Jumbotron
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
