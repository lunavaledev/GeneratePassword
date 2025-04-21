<template>
  <div class="container">
    <div class="tools-container">
      <PasswordGenerator />
    </div>
  </div>
</template>

<script setup>
import PasswordGenerator from "./PasswordGenerator.vue";
</script>

<style scoped>
.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
}

h1 {
  text-align: center;
  color: #2c3e50;
  margin-bottom: 2rem;
}

.tools-container {
  display: grid;
  grid-template-columns: 1fr;
  gap: 2rem;
}
</style>
