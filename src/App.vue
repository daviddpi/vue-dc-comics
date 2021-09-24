<template>
  <div id="app">
    <Header/>
    <Main/>
    <Icons/>
    <Footer/>
    <FollowUs/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Icons from './components/Icons.vue'
import Footer from './components/Footer.vue'
import FollowUs from './components/FollowUs.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Icons,
    Footer,
    FollowUs
  }
}
</script>

<style lang="scss">
@import './style/general.scss';

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
