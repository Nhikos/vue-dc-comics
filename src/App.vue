<template>
  <div id="app">
    <Header />
    <Jumbotron />
    <Comics />
    <Banner />
    <FooterTop />
    <FooterBot />

  </div>
</template>

<script>
import Header from './components/Header.vue'
import Jumbotron from './components/Jumbotron.vue'
import Comics from './components/Comics.vue'
import Banner from './components/Banner.vue'
import FooterTop from './components/FooterTop.vue'
import FooterBot from './components/FooterBot.vue'

export default {
  name: 'App',
  components: {
    Header,
    Jumbotron,
    Comics,
    Banner,
    FooterTop,
    FooterBot
  }
}
</script>

<style lang="scss">
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
  font-family: 'Roboto Condensed', sans-serif;
}

</style>
