<script setup>
import CertificationCard from '../mini/CertificationCard.vue';

const certification = [
    '/certification/1.png',
    '/certification/2.png',
    '/certification/3.png',
    '/certification/4.png',
    '/certification/5.png',
    '/certification/6.png',
    '/certification/7.png',
]
</script>

<template>
<div class="my-5" id="certification">
  <div class="container">
    <h1 class="text-clr1 text-center mb-4">My Certification's</h1>
    <div class="row justify-content-center">
      <div v-for="(x, index) in certification"
        :key="index"
        class="col-6 col-md-4 col-lg-3 col-xxl-3 d-flex justify-content-center pb-4"
      >
        <CertificationCard :img="x" />
      </div>
    </div>
  </div>
</div>
</template>

<style scoped></style>
