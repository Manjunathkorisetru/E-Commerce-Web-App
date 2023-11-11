<script>
import { cartItems } from "../temp-data";
import ShoppingCartList from "../components/ShoppingCartList.vue";

export default {
  data() {
    return {
      cartItems,
    };
  },
  components: { ShoppingCartList },
};
</script>

<template>
  <h1>Shopping Cart</h1>
  <ShoppingCartList :cartItems="cartItems" />
</template>
