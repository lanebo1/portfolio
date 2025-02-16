<template>
  <nav>
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#languages">Languages</a></li>
      <li><a href="#frameworks">Frameworks</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#tools">Tools</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>
</template>

<style scoped>
nav {
  background: rgba(0, 255, 204, 0.1);
  padding: 10px 0;
  position: fixed;
  width: 100%;
  top: 0;
  z-index: 1000;
}

nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
  padding: 0;
}

nav li {
  margin: 0 15px;
}

nav a {
  color: #00ffcc;
  text-decoration: none;
  font-size: 1.2rem;
}

nav a:hover {
  text-shadow: 0 0 5px #ff00ff;
}
</style>
