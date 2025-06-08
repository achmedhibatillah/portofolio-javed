<script setup>
import SkillCard from '../mini/SkillCard.vue'

const skills = [
  {
    icon: '/icon/kotlin.svg',
    skill: 'Kotlin'
  },
  {
    icon: '/icon/html.svg',
    skill: 'HTML'
  },
  {
    icon: '/icon/css.svg',
    skill: 'CSS'
  },
  {
    icon: '/icon/solidity.svg',
    skill: 'Solidity'
  },
]
</script>

<template>
<div class="my-5" id="skills">
  <div class="container">
    <h1 class="text-clr1 text-center mb-4">My Skill's</h1>
    <div class="row justify-content-center">
      <div v-for="(x, index) in skills"
        :key="index"
        class="col-6 col-md-6 col-lg-3 col-xxl-3 d-flex justify-content-center pb-4"
      >
        <SkillCard :icon="x.icon" :skill="x.skill" />
      </div>
    </div>
  </div>
</div>
</template>

<style scoped></style>
