<template>
  <NavBar />
  <Jumbotron />
  <CallToAction />
  <CardsBox />
</template>

<script>

import NavBar from './components/NavBar.vue'
import Jumbotron from './components/JumBotron.vue'
import CallToAction from './components/CallToAction.vue'
import CardsBox from './components/CardsBox.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    Jumbotron,
    CallToAction,
    CardsBox
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
