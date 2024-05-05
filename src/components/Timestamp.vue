<template>
    <span class="timestamp">{{ timestamp }}</span>
</template>

<script setup>
import {defineProps} from 'vue'

const props = defineProps( {
    timestamp: String
})

</script>

<style scoped></style>