<script setup>
import Navbar from '../templates/Navbar.vue';
import Description from '../section/Description.vue';
import Skills from '../section/Skills.vue';
import Certification from '../section/Certification.vue';
import Footbar from '../templates/Footbar.vue';
</script>

<template>
<div class="w-100">
    <Navbar page="biodata" />
    <Description />
    <Skills />
    <Certification />
    <Footbar />
</div>
</template>

<style scoped>
</style>