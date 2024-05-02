
<script setup>
 
 const imageInfo ={
    src: 'https://media.istockphoto.com/id/1529821833/photo/asian-multiethnic-business-people-talk-during-a-coffee-break-in-seminar-business-conference.jpg?s=1024x1024&w=is&k=20&c=tr5DnBiQPP3cL8Q_tQpeCN-FNjNxFt4r7aL1qLiJpgE=',
    alt: 'test',
    width:600,
    height:600
 }

</script>


<template>
    <!-- <img v-bind:="imageInfo" /> -->
    <img :="imageInfo" />
   

</template>