<!-- SCRIPT -->
<script setup>

    //Importar o REF
    import { ref } from 'vue';

    // Variavel
    let texto = ref('');
    let idade = 30

</script>

<!-- HTML -->
<template>
    <input type="text" v-model="texto">
    <p>{{ texto }}</p>  
</template>
