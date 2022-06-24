<template>
    <h1>
       Counter: {{ counterStore.counter }} 
    </h1>
    <button @click="counterStore.incrementBy(1)">mas 1</button>
    <button @click="counterStore.incrementBy(2)">mas 2</button>
    <button @click="counterStore.incrementBy(5)">mas 5</button>
</template>

<script setup lang="ts">
import { useCounterStore } from '../stores/counter'

const counterStore = useCounterStore()

</script>

<style scoped>

</style>