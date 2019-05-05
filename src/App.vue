<template>
  <div id="app">
      <div class='top-layer'>
        <TopBanner />
        <Navbar />
        <Home />
        <AboutHome />
        </div>
  </div>
</template>

<script>
import TopBanner from './components/Top-Banner.vue';
import Navbar from './components/Navbar.vue';
import Home from './components/Home-greeting.vue';
import AboutHome from './components/Home-about.vue'

export default {

  name: 'app',
  components: {
  TopBanner, 
  Navbar,
  Home,
  AboutHome
  }
}
</script>

<style lang='scss'>
@import 'styles/_index.scss';
</style>
