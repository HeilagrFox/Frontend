
<script setup>
 import {ref } from 'vue';
const number=ref(0);

</script>
<template>
    <div>
     <p><b>The number: {{ number}} . </b> </p>
     <button @click="number++"> <b>Hey, click me for +1!</b></button>

     <button @click="number--"> <b>Hey, click me for -1!</b></button>
    </div>
</template>

<style  scoped>
 button {
  color: #620ec9; 
  opacity: 0.9;
  height: 50px;
  width: 200px;
  background-color: black;
  padding: 10px 20px;
  font-size: 16px;
  font-style: italic;
  border-radius: 50px; 
  text-align: center;
  justify-content: center;
  cursor: pointer;
  transition: background-color 0.3s ease;
 }
 button:hover{
    color: red;
 }
 
</style>