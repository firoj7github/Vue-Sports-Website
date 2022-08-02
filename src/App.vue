<template>
  <NavBar></NavBar>
  <SliderSite></SliderSite>
  <ClipSite></ClipSite>
</template>

<script>
import NavBar from './components/NavBar.vue'
import SliderSite from './components/SliderSite.vue'
import ClipSite from './components/ClipSite.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    SliderSite,
    ClipSite,
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
