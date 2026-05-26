<template>
    <div class="card">
        <h2>{{ title }}</h2>
        <p>{{ paragraph }}</p>
    </div>
</template>

<script setup>
defineProps({
  title: {
    type: String,
    default: "Título por defecto"
  },

  paragraph: {
    type: String,
    default: "No hay descripción disponible"
  }
})
</script>

<style lang="scss" scoped>
.card{
    display: inline-block;
    vertical-align: top;
    background-color: #fff;
    padding: 1rem;
    border-radius: 5px;
    width: 200px;
    margin: 10px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
}

</style>