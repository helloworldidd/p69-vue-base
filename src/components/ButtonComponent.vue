<template>
    <button @click="aviso"> click me</button>
</template>

<script setup>

const aviso = () => {
    alert('click')
}

</script>

<style lang="scss" scoped>

button{
    background-color: #c89b1e;
    color: #fff;
    padding: 4px 8px;
    text-align: center;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
}
button:hover{
    background-color: #6d5d0c;
    
}

</style>