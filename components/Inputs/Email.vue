<script setup lang="ts">

</script>

<template>
  <div class="input-group">
    <label for="email" class="label">Email:</label>
    <input type="email" name="email" id="email">
  </div>
</template>

<style scoped>
.input-group{
  display: flex;
  flex-direction: column;
}

.label {
  font-size: 0.9rem;
  color: #374151;
  margin-bottom: 8px;
  font-weight: bold;
}

input {
  max-width: 100%;
  padding: 12px 15px;
  font-size: 1rem;
  border: 1px solid #d1d5db;
  border-radius: 8px;
  outline: none;
  background-color: #ffffff;
  transition: border-color 0.3s ease;
}

input:focus {
  border-color: #2563eb;
  box-shadow: 0 0 4px rgba(37, 99, 235, 0.5);
}
</style>