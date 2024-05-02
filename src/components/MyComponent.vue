
<script setup>
const myMessage = "Yellow world"
const myNumber = 100
function add(x,y){
    return x+y
}
</script>


<template>
<h1> {{ myMessage }}</h1>
 <h2>{{ myNumber }}</h2>
 <h2> Add two numbers: {{ add(2,12) }}</h2>

</template>





<style scoped >

h1 {
    color:rgb(4, 0, 255);
}
</style>