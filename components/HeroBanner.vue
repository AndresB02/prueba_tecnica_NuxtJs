<template>
  <div class="the-home-slider">
    <div class="swiper-container" ref="swiper">
      <div class="swiper-wrapper">
        <div class="swiper-slide" v-for="(slide, index) in slides" :key="index">
          <a :href="slide.link" target="_blank">
            <img :src="slide.pcImage" :alt="slide.alt" class="show-pc" />
          </a>
        </div>
      </div>
      <!-- Pagination -->
      <div class="swiper-pagination"></div>
    </div>
  </div>
</template>

<script setup>
import { ref, onMounted } from "vue";
import Swiper from "swiper/bundle";
import "swiper/swiper-bundle.css";

const slides = ref([
  {
    link: "https://www.instagram.com/klipxtreme/?hl=es-la",
    pcImage:
      "https://klip-xtreme-frontend.s3.amazonaws.com/media/img/Klip_SlideHome_Banner_01_DK_ENG.jpg",
  },
  {
    link: "/st-products/internal/premium-anc-headphones-KNH-750-en/",
    pcImage:
      "https://klip-xtreme-frontend.s3.amazonaws.com/media/img/Klip_SlideHome_Banner_04_DK_ENG.jpg",
  },
  {
    link: "/business-en/business/",
    pcImage:
      "https://klip-xtreme-frontend.s3.amazonaws.com/media/img/Klip_SlideHome_Banner_03_DK_ENG.jpg",

    alt: "Klip_SlideHome_Banner_03",
  },
]);

const swiper = ref(null);

onMounted(() => {
  swiper.value = new Swiper(".swiper-container", {
    loop: true,
    pagination: {
      el: ".swiper-pagination",
      clickable: true,
    },
    navigation: {
      nextEl: ".swiper-button-next",
      prevEl: ".swiper-button-prev",
    },
    effect: "fade", // You can remove this if fade effect causes issues
  });
});
</script>

<style scoped>
.the-home-slider {
  position: relative;
}

.swiper-container {
  width: 100%;
  height: 100%;
}

.swiper-slide {
  text-align: center;
  font-size: 18px;
  background: #fff;
  display: flex;
  justify-content: center;
  align-items: center;
}

.swiper-slide img {
  display: block;
  width: 100%;
  height: auto;
}

.show-pc {
  display: block;
}

.show-rs {
  display: none;
}

.swiper-pagination-bullet {
  background: #000;
}

.swiper-button-prev,
.swiper-button-next {
  color: #000;
}
</style>
