<template>
<div>
  <div id="app">

  <nav-bar></nav-bar>
  <div class="section is-flex is-align-items-center">
    <div class="container">
  <div class="columns is-flex is-multiline is-centered is-justify-content-space-around">
    <card class="column is-4 is-flex-direction-row is-flex m-4 box" dir="rtl"></card>
    <card class="column is-4 is-flex-direction-row is-flex m-4 box"></card>
    <card class="column is-4 is-flex-direction-row is-flex m-4 box"></card>
    <card class="column is-4 is-flex-direction-row is-flex m-4 box"></card>
  </div>

    </div>
  </div>
  </div>
</div>
</template>

<script>
import NavBar from '@/components/NavBar.vue'
import Card from './components/card.vue'
export default {
  components: { NavBar, Card},
    Cardame: 'App',
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  height: 100vh;
}
</style>
