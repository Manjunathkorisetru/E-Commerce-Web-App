<script>
import { products } from "../temp-data.js";
import ProductsList from "../components/ProductsList.vue";
export default {
  data() {
    return {
      products,
    };
  },
  components: {
    ProductsList,
  },
};
</script>

<template>
  <h1>Products</h1>
  <ProductsList :products="products" />
</template>
