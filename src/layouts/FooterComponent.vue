<template>
<footer>
  <p>Información de contacto</p>
  <ButtonComponent />
</footer>

</template>

<script setup>
import ButtonComponent from '../components/ButtonComponent.vue';
</script>

<style lang="scss" scoped>

footer{
  background-color: #330b4b;
  color: #fff;
  padding: 1rem;
  text-align: center;
  padding-bottom: 80px;
}

footer p{
  margin-bottom: 20px;
}
</style>