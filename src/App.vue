<template>
  <div class="cyberpunk-theme">
    <Navbar />
    <Hero />
    <About />
    <Languages />
    <Projects />
    <Tools />
    <Contact />
    <div class="cursor-glow" ref="cursorGlow"></div>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Hero from './components/Hero.vue'
import About from './components/About.vue'
import Languages from './components/Languages.vue'
import Projects from './components/Projects.vue'
import Tools from './components/Tools.vue'
import Contact from './components/Contact.vue'

export default {
  components: {
    Navbar,
    Hero,
    About,
    Languages,
    Projects,
    Tools,
    Contact,
  },
  mounted() {
    document.addEventListener('mousemove', this.handleMouseMove)
  },
  beforeUnmount() {
    document.removeEventListener('mousemove', this.handleMouseMove)
  },
  methods: {
    handleMouseMove(event) {
      const cursorGlow = this.$refs.cursorGlow
      cursorGlow.style.left = `${event.clientX}px`
      cursorGlow.style.top = `${event.clientY}px`
    },
  },
}
</script>

<style scoped>
body {
  font-family: 'JetBrains Mono', monospace;
  background-color: #0d0d0d;
  color: #00ffcc;
  margin: 0;
  padding: 0;
  text-align: center;
}

@keyframes fadeIn {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

section {
  animation: fadeIn 1s ease-in-out;
}
</style>
