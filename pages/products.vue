<template>
  <div>
    <h2>Daftar Produk</h2>
    <ul>
      <li v-for="(product, index) in products" :key="index">
        {{ product.name }} - Rp{{ product.price }}
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      products: [
        { name: 'Produk 1', price: 100000 },
        { name: 'Produk 2', price: 150000 },
        { name: 'Produk 3', price: 200000 },
      ],
    }
  },
}
</script>
