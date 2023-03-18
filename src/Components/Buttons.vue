
<script setup>
 import { reactive,ref } from 'vue';
const letter=ref(0);
 function Onclick(event){
    letter.value++;
  
 }
</script>
<template>
    <div>
     <button @click="Onclick"> <b>Hey, click me!</b></button>
     <p>Button is clicked {{ letter }} time(s). </p>
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
    background-color: rgb(33, 11, 35);
 }
 
</style>