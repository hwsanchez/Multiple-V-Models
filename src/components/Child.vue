<script setup>
const titulo= defineModel('titulo', { required: true});
const author = defineModel('author', { required: true});


</script>

<template>
<div>
<label for="titulo">Titulo: </label>
<input id="titulo" type="text" v-model="titulo"/>
</div>
 <div> 
 <label for="autor">Autor: </label>
 <input id="autor" type="text" v-model="author"/>
</div>


</template>

<style scoped>

</style>
