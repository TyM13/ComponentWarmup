<template>
  <div>
    <product-hero></product-hero>
    <product-info></product-info>
    <product-gallery></product-gallery>
    <page-footer></page-footer>
  </div>
</template>

<script>
import ProductHero from "@/components/ProductHero.vue";
import ProductInfo from "@/components/ProductInfo.vue";
import ProductGallery from "@/components/ProductGallery.vue";
import PageFooter from "@/components/PageFooter.vue"

export default {
  components: {
    ProductHero,
    ProductInfo,
    ProductGallery,
    PageFooter,
  },
};
</script>

<style scoped>
</style>