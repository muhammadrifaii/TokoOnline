<template>
  <section class="produk-section">
    <h2>Produk Unggulan</h2>
    <div class="produk-grid">
      <div class="card" v-for="i in 3" :key="i">
        <div class="image-placeholder">Gambar {{ i }}</div>
        <h3>Produk {{ i }}</h3>
        <p>Deskripsi singkat produk {{ i }}.</p>
        <button>Beli Sekarang</button>
      </div>
    </div>
  </section>
</template>
