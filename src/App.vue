<template>
  <div id="app">
    <Header />
    <Home />
  </div>
</template>

<script>
import Home from './components/Home.vue'
import Header from './components/Header.vue'

export default {
  name: 'App',
  components: {
    Home, Header
  }
}
</script>

<style>
#app {
  @import url('https://fonts.googleapis.com/css2?family=Frank+Ruhl+Libre:wght@400;500;700&display=swap');

  font-family: 'Frank Ruhl Libre', serif;
}
</style>
