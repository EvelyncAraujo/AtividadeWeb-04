<script setup>
import { ref } from "vue";
const name = ref(`seu nome `)
const idade = ref(0);
const email =ref(``);

</script>
<template>
  <h1>Formulários</h1>
  <br>
  <label class="fundo" >
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
    <input type="email" v-model="email" />
   
  </div>
  <br>
  <div>
    <button type="submit">Enviar</button>
  </div>
<br>

</label>

</template>

<style>

h1{
  text-align: center;
  font-size: 20px;  
  font-family: Arial, Helvetica, sans-serif;

}
.fundo{
  text-align: center;
  line-height: 10px;
  background-color: rgb(152, 127, 163);
  border-radius: 8px;
}
input{
  border-radius: 5px;
  border: none;
}
button{
  text-align: center
}

</style>
