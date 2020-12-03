<template>
  <div id="app">

    <ProductCard
      v-bind:content-text= 'productTitle'
    ></ProductCard>

  </div>
</template>

<script>
import ProductCard from './components/ProductCard'

export default {
  name: 'App',
  components: {
    ProductCard
  },
  data() {
    return {
      productTitle: '測試商品名稱'
    }
  },
}
</script>

<style>
@import './assets/css/normalize.css';

</style>
