<template>
  <div id="app">
    <product-list-one ></product-list-one>
    <product-list-two ></product-list-two>
  </div>
</template>

<script>
import ProductListOne from "./components/product-list-one";
import ProductListTwo from "./components/product-list-two";

export default {
  components: {
    "product-list-one": ProductListOne,
    "product-list-two": ProductListTwo
  },
  data() {
    return {
    };
  }
};
</script>

<style>
</style>
