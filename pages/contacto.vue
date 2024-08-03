<template>
  <div>
    <Header />
    <section class="contacto">
      <h1>Contacto</h1>
      <p>Información de contacto aquí...</p>
    </section>
    <Footer />
  </div>
</template>

<script>
import Header from '~/components/Header.vue';
import Footer from '~/components/Footer.vue';

export default {
  components: {
    Header,
    Footer,
  },
};
</script>

<style scoped>
.contacto {
  padding: 2rem;
  text-align: center;
}
</style>
