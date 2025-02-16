<template>
  <div id="app">
    <Header />
    <About />
    <Projects />
    <Contact />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import About from './components/About.vue'
import Projects from './components/Projects.vue'
import Contact from './components/Contact.vue'

export default {
  name: 'App',
  components: {
    Header,
    About,
    Projects,
    Contact,
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
