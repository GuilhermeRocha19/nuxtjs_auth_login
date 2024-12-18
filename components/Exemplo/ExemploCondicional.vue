<script setup lang="ts">
function validaFormulario(){
  alert('Enviado')
}
</script>


<template>
  <form @submit="validaFormulario()">
    <buttons-submit-login/>
  </form>
</template>