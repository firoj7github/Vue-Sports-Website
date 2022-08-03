<template>
  <NavBar></NavBar>
  <SliderSite></SliderSite>
  <ClipSite></ClipSite>
  <FieldSite></FieldSite>
  <BlogSite></BlogSite>
  <FooterSite></FooterSite>
</template>

<script>
import NavBar from './components/NavBar.vue'
import SliderSite from './components/SliderSite.vue'
import ClipSite from './components/ClipSite.vue'
import FieldSite from './components/FieldSite.vue'
import BlogSite from './components/BlogSite.vue'
import FooterSite from './components/FooterSite.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    SliderSite,
    ClipSite,
    FieldSite,
    BlogSite,
    FooterSite,
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
