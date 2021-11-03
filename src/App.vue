<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/gizzard.png"  width="30%" >
    <HelloWorld msg="Yuuu.dev"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
@media (max-width: 768px) {
  img {
    width: 75%;
  }
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 12%;
}
</style>
