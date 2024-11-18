<template>

  <div class="login-container">
    <h1>{{ title }}</h1>

    <InputsEmail/>
    <InputsPassword/>
    <ButtonsSubmitLogin/>
  </div>
</template>

<style scoped>
.login-container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  max-width: 500px;
  width: 100%;
  gap: 20px;
  background-color: white;
  padding: 100px;
  border-radius: 12px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  margin: 0 auto;
}
</style>

<script setup>
  const title = 'LOGIN';
</script>
