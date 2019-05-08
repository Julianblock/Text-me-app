<template>
  <div id="app">
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
      <div class='top-layer'>
        <TopBanner />
        <Navbar />
        <Home />
        <AboutHome />
        <AboutBroadcast />
        <EmailBox />
        <HomeMoney />
        <HomeSection4 />
        <Footer />
        </div>
  </div>
</template>

<script>
import TopBanner from './components/Top-Banner.vue';
import Navbar from './components/Navbar.vue';
import Home from './components/Home-greeting.vue';
import AboutHome from './components/Home-about.vue';
import AboutBroadcast from './components/Home-about-broadcast.vue';
import EmailBox from './components/email-box.vue';
import HomeMoney from './components/Home-most-money.vue';
import HomeSection4 from './components/Home-section-4.vue';
import Footer from './components/Footer.vue';

export default {

  name: 'app',
  components: {
  TopBanner, 
  Navbar,
  Home,
  AboutHome,
  AboutBroadcast,
  EmailBox,
  HomeMoney,
  HomeSection4,
  Footer
  }
}
</script>

<style lang='scss'>
@import 'styles/_index.scss';
</style>
