
<script setup>
import {ref} from 'vue'

const submitHandler = (e) =>{
    e.preventDefault()
    alert('Valid credentials');
    
}

 const showMessage=(message)=>alert(message)
 
</script>


<template>

    <form @:submit="submitHandler">
        <input type="text" placeholder="please enter your name" style="padding:10px; margin-bottom:5px">
        <br>
        <input type="email" placeholder="please enter your name" style="padding:10px; margin-bottom:5px">
        <br>
        <button type="submit" style="padding:10px; margin-bottom:5px"> Submit</button>
         <br> <br>

         
        <button @click="showMessage('This is my message')"> Show Messagea</button>
    </form>
 

</template>





<style scoped >


</style>