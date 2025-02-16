<template>
  <header>
    <h1>My Portfolio</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<style scoped>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem;
  background-color: #333;
  color: #fff;
}

nav a {
  margin: 0 1rem;
  text-decoration: none;
}
</style>
