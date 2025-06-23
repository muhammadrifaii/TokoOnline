<template>
  <section class="produk-section">
    <h2>Produk Unggulan</h2>
    <div class="produk-grid">
      <div class="card" v-for="item in produk" :key="item.id">
        <img :src="item.gambar" :alt="item.nama" class="produk-img" />
        <h3>{{ item.nama }}</h3>
        <p>{{ item.deskripsi }}</p>
        <button>Beli Sekarang</button>
      </div>
    </div>
  </section>
</template>
