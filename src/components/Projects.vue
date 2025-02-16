<template>
  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Web Scraper</h3>
      <p>A Python-based web scraper with Flask backend.</p>
      <div class="badges">
        <span class="badge">Python</span>
        <span class="badge">Flask</span>
      </div>
    </div>
    <div class="project">
      <h3>Task Manager</h3>
      <p>Java desktop application for managing tasks.</p>
      <div class="badges">
        <span class="badge">Java</span>
        <span class="badge">Spring Boot</span>
      </div>
    </div>
    <div class="project">
      <h3>Go API Service</h3>
      <p>Go microservice for handling API requests.</p>
      <div class="badges">
        <span class="badge">Go</span>
        <span class="badge">Gin</span>
      </div>
    </div>
  </section>
</template>

<style scoped>
.project {
  background: rgba(0, 255, 204, 0.1);
  padding: 15px;
  border: 1px solid #00ffcc;
  margin: 10px auto;
  box-shadow: 0 0 10px #00ffcc;
  width: 80%;
}

.project h3 {
  color: #ff00ff;
}

.badges {
  display: flex;
  justify-content: center;
  gap: 10px;
  flex-wrap: wrap;
}

.badge {
  background: rgba(255, 0, 255, 0.2);
  border-color: #ff00ff;
  padding: 8px 15px;
  border: 1px solid #00ffcc;
  border-radius: 5px;
  text-shadow: 0 0 5px #00ffcc;
}
</style>
