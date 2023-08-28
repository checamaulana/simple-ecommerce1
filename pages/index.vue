<template>
  <div>
    <h1>Selamat datang di Toko Online Kami!</h1>
    <p>Temukan berbagai produk menarik kami di sini.</p>
    <button class="w-5 h-6 bg-blue" @click="goToProducts">Lihat Produk</button>
    <footer>
      <p class="text-lg">
        Saya Checa Maulana Seorang Yang Baru lulus SMA Umur Saya 18
      </p>
    </footer>
  </div>
</template>

<script>
export default {
  methods: {
    goToProducts() {
      this.$router.push('/products')
    },
  },
}
</script>
// export default { // name: 'IndexPage', // }
