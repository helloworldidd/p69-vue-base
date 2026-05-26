<template>

<main>
  <p>Contenido principal</p>
    <p>
        <ButtonComponent txt="Boton 1" />
        <ButtonComponent txt="Boton 2" />
        <ButtonComponent txt="Boton 3" />
        <ButtonComponent txt="Boton 4" />
        <ButtonComponent txt="Boton 5" />
    </p>
    <p>
        <Card title="Tarjeta 1" paragraph="Parrafo de la tarjeta 1" />
        <Card title="Tarjeta 2"  />
    </p>
  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis, quo!
  Distinctio culpa sequi aperiam doloribus dignissimos quaerat labore maxime eligendi.
  Fugiat iste maxime, labore rem eligendi atque alias ut. Consequuntur.
  Explicabo quo odio illo quos debitis repellat fugit nesciunt accusantium!
  Minima assumenda eos officiis voluptatem fuga necessitatibus optio est possimus.
  Incidunt fugiat quasi necessitatibus sapiente nostrum provident atque aspernatur facere.
  Incidunt reiciendis eum necessitatibus ad neque? Consequuntur libero nemo tempora.
  Numquam provident eveniet libero perspiciatis non, quam voluptates tempora delectus.
  Accusantium dicta aperiam placeat aliquam quibusdam eum fugiat tempora quo.
  Quod ratione eveniet repellat placeat tempora? Fugiat tempore porro sed?</p>
</main>

</template>

<script setup>
import ButtonComponent from '../components/ButtonComponent.vue';
import Card from '../components/Card.vue';
</script>

<style lang="scss" scoped>
main{

    background-color: #d6e1eb;
    min-height: 60vh;
    padding: 30px 10px;
}

main p{
    line-height: 1.8rem;
    color: #333;
}
</style>