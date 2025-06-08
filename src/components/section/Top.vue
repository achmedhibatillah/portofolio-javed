<script setup>
import ButtonStyle from '../mini/ButtonStyle.vue'

</script>

<template>
<div class="w-100 bg-clr1">
    <div class="container">
        <div class="row" id="top-component">
            <div class="col-md-6" id="top-right-component">
                <div class="d-flex justify-content-center align-items-end">
                    <div class="shadow-m bg-clr2 overflow-hidden p-3" id="top-me" style="height:200px;width:200px;">
                        <img src="/public/me/me-bg.png" class="w-100">
                    </div>
                </div>
            </div>
            <div class="col-md-6 d-flex justify-content-center justify-content-md-start align-items-center" id="top-left-component">
                <div class="mt-5 mt-md-0 text-light">
                    <h1 class="fw-bold text-center text-md-start">Aqil Javed Septio</h1>
                    <h5 class="text-center text-md-start">Front End Developer | Tech Enthusiast</h5>
                    <p class="mt-3 text-center text-md-start">Hai! Saya Aqil Javed Septio, seorang mahasiswa Teknik Informatika di Universitas Brawijaya. Saya seorang Front End Developer dengan pengalaman utama pada bahasa Kotlin (Jetpack Compose), HTML, dan CSS. Selain itu, saya juga memiliki ketertarikan khusus pada bidang blockchain, dan saya telah mempelajari serta menguasai dasar-dasar pemrograman Solidity untuk membuat smart contract di Ethereum.</p>
                    <div class="mt-4 d-flex justify-content-center justify-content-md-start">
                        <ButtonStyle url="https://instagram.com" target="_blank" isi="<i class='fab fa-instagram me-1'></i> instagram" fsz="12" px="3" py="2" bgclr="#9F3693" clr="#ffffff" class="me-2" />
                        <ButtonStyle url="https://facebook.com" target="_blank" isi="<i class='fab fa-facebook me-1'></i> facebook" fsz="12" px="3" py="2" bgclr="#4B64B0" clr="#ffffff" />
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
</template>

<style scoped>
#top-component {
    min-height: 300px;
    padding: 100px 0;
}
#top-me {
    border-radius: 90px 0 90px 0;
}
</style>