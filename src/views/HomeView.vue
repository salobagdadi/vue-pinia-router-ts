<template>
    <h1>
       Home: {{ counterStore.counter }}
    </h1>
    <h3>
       Cambios: {{ counterStore.numberOfChanges }}
    </h3>
</template>

<script setup lang="ts">

import { useCounterStore } from '../stores/counter'

const counterStore = useCounterStore()

</script>

<style scoped>

</style>