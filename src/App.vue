<script setup>
import { ref } from "vue";
const name = ref(`seu nome `)
const idade = ref(0);

const email =ref(``);

</script>
<template>
  <h1>Formulários</h1>
  <br>
  <div>
    <label>Informe seu nome:</label>
    <input type="text" v-model="name" />
  </div>
  <br>
  <div>
    <label>Informe sua idade:</label>
    <input type="number" v-model="idade" />
   
  </div>
  <br>
  <div>
    <label for="email">E-mail:</label>
    <input type="email" v-model="email">
   
  </div>
  <br>
  <div class="button">
    <button @click="submitForm">Enviar</button>
</div>


</template>

<style>
h1{
  text-align: center;
  font-size: 20px;
  
}
</style>