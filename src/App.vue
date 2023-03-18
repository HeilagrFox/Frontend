<script setup>
  import Buttons from "./Components/Buttons.vue";
  import Timer from "./Components/Timer.vue";
</script>

<template>
  <div class="container">
    <h1>Welcome!</h1>
    <p class="b">
     <Buttons></Buttons>
    </p>
   
  </div>
  <Timer></Timer>
</template>



<style scoped>

  
h1{
  text-align: center;
}
.b{
  position:absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  
}
.container{
  background-color: aquamarine;
}
</style>