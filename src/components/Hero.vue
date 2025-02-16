<template>
  <div class="hero">
    <p class="subtitle">Python | Java | Go Developer</p>
  </div>
</template>

<style scoped>
.hero {
  padding: 100px 20px;
  background: linear-gradient(to right, #000033, #000022);
}

.hero h1 {
  font-size: 3rem;
  text-shadow: 0 0 10px #00ffcc, 0 0 20px #00ffcc;
}

.subtitle {
  font-size: 1.5rem;
  color: #ff00ff;
}

.glitch {
  position: relative;
  display: inline-block;
}

.glitch:before,
.glitch:after {
  content: attr(data-text);
  position: absolute;
  width: 100%;
}

.glitch:before {
  left: -2px;
  text-shadow: -2px 0 #ff00ff;
  animation: glitch-anim 0.3s infinite linear alternate-reverse;
}

.glitch:after {
  left: 2px;
  text-shadow: 2px 0 #00ffff;
  animation: glitch-anim 0.3s infinite linear alternate;
}

@keyframes glitch-anim {
  0% {
    clip: rect(0, 9999px, 0, 0);
  }
  100% {
    clip: rect(0, 9999px, 0, 0);
  }
}
</style>
