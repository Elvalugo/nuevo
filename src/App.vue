<template>
<HeaderYooo/>
<HelloWorld msg="GHOLA"/>
<footerYooo />
</template>


<script>
import HeaderYooo from './components/HeaderYooo.vue';
import HelloWorld from './components/HelloWorld.vue'
import footerYooo from './components/footerYooo.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    HeaderYooo,
    footerYooo
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
  margin-top: 9px;
}

</style>
