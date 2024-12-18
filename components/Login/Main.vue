<template>
  <div class="flex flex-col justify-center items-center max-w-md w-full gap-5 bg-white p-12 rounded-lg shadow-md mx-auto">
    <h1 class="text-2xl font-bold">{{ title }}</h1>

    <InputsEmail/>
    <InputsPassword/>
    <ButtonsSubmitLogin/>
  </div>
</template>

<script setup>
  const title = 'LOGIN';
</script>
