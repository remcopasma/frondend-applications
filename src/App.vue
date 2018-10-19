<template>
  <div id="app">
    <Header />
    <Main />
    <MainLeft />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header'
import Main from './components/Main'
import MainLeft from './components/MainLeft'
import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    Header,
    Main,
    MainLeft,
    Footer
  },
}
</script>
<style>
@import './components/style.css';
</style>