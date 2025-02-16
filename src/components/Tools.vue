<template>
  <section id="tools">
    <h2>Additional Tools</h2>
    <div class="tags">
      <span class="tag">Docker</span>
      <span class="tag">Git</span>
      <span class="tag">Linux</span>
      <span class="tag">PostgreSQL</span>
    </div>
  </section>
</template>

<style scoped>
.tags {
  display: flex;
  justify-content: center;
  gap: 10px;
  flex-wrap: wrap;
}

.tag {
  background: rgba(0, 255, 204, 0.1);
  padding: 8px 15px;
  border: 1px solid #00ffcc;
  border-radius: 5px;
  text-shadow: 0 0 5px #00ffcc;
}
</style>
