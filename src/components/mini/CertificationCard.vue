<script setup>
import { defineProps } from 'vue';

const props = defineProps({
    img: {
        type: String,
        required: true,
    }
})
</script>

<template>
<div class="card-certification">
    <div class="w-100">
        <img :src="img" class="w-100">
    </div>
</div>
</template>

<style scoped></style>