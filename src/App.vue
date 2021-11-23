<template>
  <div id="app">
    <Titolo msg="La prima app con vue CLI"/>
    <Hero />
  </div>
</template>

<script>
import Hero from './components/Hero.vue';
import Titolo from './components/Title.vue';

export default {
  name: 'App',
  components: {
    Titolo,
    Hero
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
