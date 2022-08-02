<template>
  <NavBar></NavBar>
  <SliderSite></SliderSite>
</template>

<script>
import NavBar from './components/NavBar.vue'
import SliderSite from './components/SliderSite.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    SliderSite,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  
  color: #2c3e50;
 
  
}
</style>
