<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <PruebaComponent msg="Property msg"/>
  <indecisionComponent/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import IndecisionComponent from './components/IndecisionComponent.vue'
import PruebaComponent from './components/PruebaComponent.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    PruebaComponent,
    IndecisionComponent
  }
}
</script>

<,
    Indecisionstyle>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
