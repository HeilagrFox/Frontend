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
    <p class="t"><Timer></Timer></p>
  </div>
  
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
.t{
  position:absolute;
  top: 90%;
  left: 5%;
  
}
</style>