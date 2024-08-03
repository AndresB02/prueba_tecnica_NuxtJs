<template>
  <div>
    <Header />
    <section class="productos">
      <h1>Nuestros Productos</h1>
      <p>Lista de productos aquí...</p>
    </section>
    <Footer />
  </div>
</template>

<script>
import Header from "~/components/Header.vue";
import Footer from "~/components/Footer.vue";

export default {
  components: {
    Header,
    Footer,
  },
};
</script>

<style scoped>
.productos {
  padding: 2rem;
  text-align: center;
}
</style>
