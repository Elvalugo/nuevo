<template>
  <HelloWorld msg="GHOLA"/>
 
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import footeryooo from './components/footeryooo.vue';


export default {
  name: 'App',
  components: {
    HelloWorld,
    Footeryooo
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
.encabezado {
  background-color: aqua;
  color: white;
padding: 2px;
text-align: center;
}
</style>
