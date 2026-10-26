<script setup lang="ts">
import { ref } from 'vue'

const contador = ref(0)
</script>

<template>
  <div class="container">
    <h1>Contador com Vue.js</h1>

    <p>Framework JavaScript para construir interfaces.</p>

    <button @click="contador++">
      Cliques: {{ contador }}
    </button>
  </div>
</template>

<style>
* {
  background-color: #040404;
}

p {
  color: #ffffff;
  font-size: 18px;
  margin-bottom: 20px;
}

.container {
  text-align: center;
  margin-top: 50px;
  font-family: Arial, sans-serif;
}

h1 {
  color: #42b883;
}

button {
  padding: 10px 15px;
  background: #42b883;
  color: white;
  border: none;
  border-radius: 5px;
}
</style>