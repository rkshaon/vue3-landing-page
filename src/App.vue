<template>
  <NavBar />
  <JumbotronComponent />
  <CallToAction />
  <CardsBox />
  <FooterComponent />
</template>

<script>

import NavBar from './components/NavBar.vue'
import JumbotronComponent from './components/JumbotronComponent.vue'
import CallToAction from './components/CallToAction.vue'
import CardsBox from './components/CardsBox.vue'
import FooterComponent from './components/FooterComponent.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    JumbotronComponent,
    CallToAction,
    CardsBox,
    FooterComponent
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
