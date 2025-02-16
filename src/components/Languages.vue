<template>
  <section id="languages">
    <h2>Languages</h2>
    <div class="language-card">
      <span class="tag">Python</span>
      <div class="frameworks">
        <span class="tag">Flask</span>
        <span class="tag">Django</span>
      </div>
    </div>
    <div class="language-card">
      <span class="tag">Java</span>
      <div class="frameworks">
        <span class="tag">Spring Boot</span>
      </div>
    </div>
    <div class="language-card">
      <span class="tag">Go</span>
      <div class="frameworks">
        <span class="tag">Gin</span>
      </div>
    </div>
  </section>
</template>

<style scoped>
.language-card {
  position: relative;
  display: inline-block;
  margin: 10px;
}

.frameworks {
  display: none;
  position: absolute;
  top: 100%;
  left: 50%;
  transform: translateX(-50%);
  background: rgba(0, 255, 204, 0.1);
  padding: 10px;
  border: 1px solid #00ffcc;
  border-radius: 5px;
  text-shadow: 0 0 5px #00ffcc;
}

.language-card:hover .frameworks {
  display: flex;
  flex-direction: column;
  gap: 5px;
}

.tag {
  background: rgba(0, 255, 204, 0.1);
  padding: 8px 15px;
  border: 1px solid #00ffcc;
  border-radius: 5px;
  text-shadow: 0 0 5px #00ffcc;
}
</style>
