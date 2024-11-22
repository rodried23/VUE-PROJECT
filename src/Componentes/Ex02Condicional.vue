<script setup>
    //Variavel
    let exibir = true;
    let media = 8;

</script>

<!-- HTML -->

<template>
    <h1 v-if="exibir">Hello World!</h1>

    <p v-if="media >= 7">Aprovado(a)</p>
    <p v-else-if="media >= 5">Em Exame</p>
    <p v-else="media < 7">Reprovado(a)</p>
</template>