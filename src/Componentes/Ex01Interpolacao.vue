<!-- SCRIPT -->
<script setup>

// Variaveis
let nome = 'Antoni';
let idade = 30;
let num1 = 10;
let num2 = 20;

</script>

<!-- HTML -->
<template>
  <p>{{ 'Olá ' + nome + ' você tem ' + idade + ' anos.'}}</p>
  <p>{{ num1*num2  }}</p>
</template>