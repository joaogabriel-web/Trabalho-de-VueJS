<script setup lang="ts"></script>

<template>
   <div class="container">
     <h1>Seminário sobre Vue.js</h1>

     <p>Meu primeiro projeto em Vue.</p>

      <button @click="aumentar">Clique Aqui</button>
      <p>Contador: {{ contador }}</p>
  </div>
</template>

<style scoped>
body {
  background-color: #202020;
}

h1 {
  color: green;
}

.container {
  text-align: center;
  margin-top: 50px;
}
</style>

<script setup lang="ts">
import { ref } from 'vue'

const contador = ref(0)

function aumentar() {
  contador.value++
}
</script>
