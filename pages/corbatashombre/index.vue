<script setup>
import ProductList from '~/components/ProductList.vue'
import { items } from '../../public/corbatas/data'

</script>
<template>
  <div>
    <h1 class="corbatas-title">Corbatas Hombre</h1>
    <ProductList :items="items" />
  </div>
</template>

<style scoped>
.corbatas-title {
  color: goldenrod;
  text-align: center;
  font-size: 2.2rem;
  margin: 2rem 0 1.5rem 0;
  letter-spacing: 2px;
  font-family: 'Playfair Display', serif;
}
</style>
