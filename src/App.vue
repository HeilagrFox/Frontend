<script setup>
   import {ref} from 'vue';
const text=ref("");
const cards = ref({
    card1:'Russia',
    card2:'USA',
    card3:'German',
    card4:'South Korea',
    card5:'China',
    card6:'Japan',
    card6:'France'
})
</script>

<template> 
<div>
  <h1><u><i>Cards</i></u></h1>
<input v-model="text" placeholder="Write here" class="inp">
<div v-for="card in cards"
 :key = "card.id" >
  <p v-if="card.toLowerCase().includes(text.toLowerCase())" class="card"> {{ card }}</p>
</div> 
 
</div>
  
   
   
</template>


<style scoped>

</style>
