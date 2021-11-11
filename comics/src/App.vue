<template>
  <div id="app">
    <SiteHeader/>
    <MainContent/>
    <SiteFooter/>
    
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import SiteHeader from './components/SiteHeader.vue';
import MainContent from './components/MainContent.vue';
import SiteFooter from './components/SiteFooter.vue';

export default {
  name: 'App',
  components: {
    SiteHeader,
    MainContent,
    SiteFooter
  }
}
</script>

<style lang="scss">
* {
  box-sizing: border-box;
  margin: 0%;
  padding: 0%;
}
</style>
