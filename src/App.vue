<script setup>
import Child from './components/Child.vue'
import { ref } from 'vue';

const title = ref('Star Wars');
const author = ref('George Lucas');
</script>

<template>
<h1>{{ title }}</h1>
<p>{{ author}} </p>

<Child v-model:titulo="title" v-model:author="author"></Child>
</template>

<style scoped>

</style>
