
<script setup>
import {ref, watchEffect} from "vue";

let timer=ref(new Date().toLocaleString());
watchEffect(()=>{
    setInterval(()=>{
      timer.value=new Date().toLocaleString();
    },1000);
})
</script>
<template>

    <div class="time">
     {{ timer }}
    </div>
</template>

<style scoped>
.time{
    font-size:large;
    font-weight: bold;
}
</style>