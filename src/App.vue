<template>
  <div id="app">
    <Navbar />
    <Carousel />
    <CardProduk />
    <PromoFirework />
    <Footer />
  </div>
</template>

<script setup>
import Navbar from './components/Navbar.vue'
import Carousel from './components/Carousel.vue'
import CardProduk from './components/CardProduk.vue'
import PromoFirework from './components/PromoFirework.vue'
import Footer from './components/Footer.vue'
</script>
<style>
.produk-image {
  width: 100%;
  height: auto;
  border-radius: 8px;
}
</style>

<style src="./style.css"></style>
