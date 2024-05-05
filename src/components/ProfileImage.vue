<template>

<img :src="image" class="profile" alt="" />

</template>

<script setup>
import {defineProps} from 'vue'

const props = defineProps({
    image: String
})

</script>

<style scoped></style>