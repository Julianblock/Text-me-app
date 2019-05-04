<template>
  <div id="app">
      <div class='top-layer'>
        <TopBanner />
        <Navbar />
        <Home />
        </div>
  </div>
</template>

<script>
import TopBanner from './components/Top-Banner.vue';
import Navbar from './components/Navbar.vue';
import Home from './components/Home-greeting.vue';

export default {

  name: 'app',
  components: {
  TopBanner, 
  Navbar,
  Home
  }
}
</script>

<style lang='scss'>
@import 'styles/_index.scss';
</style>
