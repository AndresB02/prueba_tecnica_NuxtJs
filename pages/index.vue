<template>
  <div>
    <Header />
    <HeroBanner />
    <ProductGrid />
    <HeadPhones />
    <CarouselProducts />
    <Catalog />
    <Kruiser />
    <UltimateAudio />
    <Video />
    <Featured />
    <Footer />
  </div>
</template>

<script>
import Header from "/components/Header.vue";
import HeroBanner from "/components/HeroBanner";
import ProductGrid from "/components/ProductGrid";
import HeadPhones from "~/components/HeadPhones.vue";
import CarouselProducts from "~/components/CarouselProducts.vue";
import Catalog from "~/components/Catalog.vue";
import Kruiser from "~/components/Kruiser.vue";
import UltimateAudio from "~/components/UltimateAudio.vue";
import Video from "~/components/Video.vue";
import Featured from "~/components/Featured.vue";
import Footer from "/components/Footer";

export default {
  components: {
    Header,
    HeroBanner,
    ProductGrid,
    HeadPhones,
    CarouselProducts,
    Catalog,
    Kruiser,
    UltimateAudio,
    Video,
    Featured,
    Footer,
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  background: white;
}
</style>
