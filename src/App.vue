<template>
  <img alt="Vue logo" src="./assets/ape.png" style="object-fit:cover; height:100%;width:100%; position: fixed; top: 0; left: 0; bottom: 0; right: 0; z-index: -1">
  <HelloWorld msg="We're all apes"/>
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
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #fff;
  margin-top: 60px;
  font-size: 300%;
}
</style>
