<template>
    <div class="card">
        <h2>{{ txt }}</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quae, repellendus.</p>
    </div>
</template>

<script setup>
defineProps({
    txt: String
})
</script>

<style lang="scss" scoped>
.card{
    display: inline-block;
    background-color: #fff;
    padding: 1rem;
    border-radius: 5px;
    width: 200px;
    margin: 10px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
}

</style>