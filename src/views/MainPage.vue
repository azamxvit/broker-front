<template>
  <div class="app">
    <header class="header">
      <h1>Broker Check </h1>
    </header>

    <main class="content">
      <p>Добро пожаловать! Это базовая страница приложения на Vue 3 + Vite.</p>

      <button @click="count++">
        Нажали {{ count }} раз
      </button>
    </main>
  </div>
</template>

<script setup>
import { ref } from 'vue'

const count = ref(0)
</script>

<style scoped>
.app {
  font-family: system-ui, sans-serif;
  padding: 2rem;
  text-align: center;
}

.header {
  background: linear-gradient(135deg, #0048FF, #002B99);
  color: white;
  padding: 1.5rem;
  border-radius: 12px;
}

.content {
  margin-top: 2rem;
}

button {
  background: #0048FF;
  color: #fff;
  padding: 0.6rem 1.2rem;
  border: none;
  border-radius: 8px;
  cursor: pointer;
  transition: 0.3s;
}
button:hover {
  background: #002B99;
}
</style>
