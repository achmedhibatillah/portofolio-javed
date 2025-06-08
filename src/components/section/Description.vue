<script setup>
import { defineProps } from 'vue';
</script>

<template>
<div class="bg-clr1">
    <div class="container">
        <div class="d-flex justify-content-center align-items-center" id="card-description">
            <div class="bg-light rounded-m overflow-hidden w-100 shadow-xl">
                <div class="row">
                    <div class="col-md-4 d-flex flex-column justify-content-center align-items-center">
                        <div class="w-75 overflow-hidden d-flex justify-content-center align-items-end shadow my-5" style="width:100px;aspect-ratio:4/5;">
                            <img src="/public/me/me-full.jpg" class="w-100">
                        </div>
                    </div>
                    <div class="col-12 col-md-8 ps-4 ps-md-4 pe-md-5 py-4 d-flex flex-column justify-content-center text-dark position-relative">
                        <h1 class="fw-800">Aqil Javed Septio</h1>
                        <p class="">Front End Developer | Tech Enthusiast</p>
                        <p>Hai! Saya Aqil Javed Septio, seorang mahasiswa Teknik Informatika di Universitas Brawijaya. Saya seorang Front End Developer dengan pengalaman utama pada bahasa Kotlin (Jetpack Compose), HTML, dan CSS. Selain itu, saya juga memiliki ketertarikan khusus pada bidang blockchain, dan saya telah mempelajari serta menguasai dasar-dasar pemrograman Solidity untuk membuat smart contract di Ethereum.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
</template>

<style scoped>
#card-description {
    padding: 60px 0;
}
#id-star {
    border: solid 1px black;
    background-color: black;
    color: #ffffff;
    aspect-ratio: 1/1;
    width: 40px;
}
#id-header {
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}
</style>