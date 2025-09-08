<template>
    <h1>Notes Page</h1>
    <br>
    <button @click="bull = !bull">Toggle{{bull}}</button>
    <br>
    <Newnote v-if="!bull"/>
    <br>
    <NoteCards v-if="bull" /> 
</template>
<script setup>
    const bull = ref(false);
</script>