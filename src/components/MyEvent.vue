
<script setup>
import {ref} from 'vue'
 let count = ref(5)
 const handleIncrement =()=>{
  count.value++
 }
 const handleDecrement =()=>{
  count.value--
 }

</script>


<template>

<h1> Count: {{ count}} </h1>
 <button v-on:click="handleIncrement"> Increment</button>
 <button v-on:click="handleDecrement"> Decrement</button>

</template>





<style scoped >


</style>