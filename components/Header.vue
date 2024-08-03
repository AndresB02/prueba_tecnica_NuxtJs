<template>
  <header class="the-header">
    <nav
      class="relative flex flex-wrap items-center content-between py-3 px-4 p-0 text-black bg-white"
    >
      <div class="flex flex-wrap w-full m-auto">
        <div
          class="relative sm:flex-grow sm:flex-1 flex items-center self-start xl:self-stretch sm:py-2 px-0 order-1 w-2/3"
        >
          <a
            href="#"
            class="inline-block pt-1 pb-1 mr-4 text-lg whitespace-no-wrap nuxt-link-exact-active nuxt-link-active"
            ><img src="/assets/images/logo.png" alt="Logo de Klip Xtreme"
          /></a>
        </div>
        <!-- menu -->
        <div
          class="px-0 lg:px-4 flex flex-col self-center xl:self-start order-3 sm:order-2 border-bottom-klip pt-2 md:pt-4 xl:pt-1 sm:w-1/2 md:w-3/5 pr-4 pl-4 lg:w-2/3 w-full container"
        >
          <!-- input -->
          <div class="flex flex-wrap row-cols-12 justify-center">
            <div class="mx-auto xl:w-2/5 pr-4 pl-4 w-full">
              <div class="relative flex items-stretch w-full py-1">
                <input
                  class="main-search-form block appearance-none w-full py-1 px-2 mb-1 leading-normal text-gray-100 border border-gray-200 rounded-full bg-neutral-600 text-sm"
                  id="input"
                  type="text"
                  placeholder="Search"
                />
              </div>
            </div>
          </div>
          <!-- options -->
          <div class="card bg-white">
            <MegaMenu :model="items" />
          </div>
        </div>
        <!-- social media -->
        <div
          class="relative sm:flex-grow sm:flex-1 xl:self-end order-2 sm:order-3 flex px-0 w-1/3"
        >
          <div class="flex flex-wrap w-full px-0 flex-flex">
            <div class="px-0 flex relative flex-grow max-w-full flex-1">
              <div class="flex flex-wrap w-full px-0">
                <div
                  class="flex items-center self-start xl:self-stretch py-2 sm:py-4 xl:py-2 justify-end px-0 w-full"
                >
                  <span class="text-gray-900 text-decoration-none pr-3 xl:pr-2"
                    >ES</span
                  >
                  <a href="#" class="pr-3 xl:pr-2"
                    ><font-awesome-icon
                      :icon="['fas', 'globe']"
                      size="lg"
                      style="color: #7de140"
                  /></a>
                </div>
              </div>
            </div>
          </div>
          <!-- social media icons -->
          <div class="hidden xl:flex px-4 relative flex-grow max-w-full flex-1">
            <div class="flex flex-wrap items-center">
              <div class="flex px-0 relative flex-grow max-w-full flex-1 gap-2">
                <a href="https://www.facebook.com/klipxtreme/" target="_blank"
                  ><font-awesome-icon
                    :icon="['fab', 'facebook-f']"
                    size="lg"
                    style="color: #7de140"
                /></a>
                <a href="https://www.instagram.com/klipxtreme" target="_blank"
                  ><font-awesome-icon
                    :icon="['fab', 'instagram']"
                    size="lg"
                    style="color: #7de140"
                /></a>
                <a href="https://twitter.com/klipxtreme" target="_blank"
                  ><font-awesome-icon
                    :icon="['fab', 'x-twitter']"
                    size="lg"
                    style="color: #7de140"
                /></a>
                <a
                  href="https://www.youtube.com/user/KlipXtremeLA"
                  target="_blank"
                  ><font-awesome-icon
                    :icon="['fab', 'youtube']"
                    size="lg"
                    style="color: #7de140"
                /></a>
                <a
                  href="https://www.tiktok.com/@klipxtreme_oficial?_t=8aTyYXT1Byg&amp;_r=1"
                  target="_blank"
                  ><font-awesome-icon
                    :icon="['fab', 'tiktok']"
                    size="lg"
                    style="color: #7de140"
                /></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </nav>
  </header>
</template>

<script setup>
import MegaMenu from "primevue/megamenu";

import { ref } from "vue";

const items = ref([
  {
    label: "AUDIO",
    icon: "pi pi-box",
    items: [
      [
        {
          label: "HEADPHONES",
          class: "headphones",
          items: [
            { label: "Sport" },
            { label: "Wireless" },
            { label: "Noise Canceling" },
            { label: "True Wireless Stereo (TWS)" },
            { label: "Wired" },
          ],
        },
      ],
      [
        {
          label: "SPEAKERS",
          items: [
            { label: "Party Speakers" },
            { label: "Portable Speakers" },
            { label: "Sound Bars" },
            { label: "Sound Systems" },
          ],
        },
        {},
      ],
      [{}],
      [{}],
    ],
  },
  {
    label: "ALL PRODUCTS",
    icon: "pi pi-mobile",
    items: [
      [
        {
          label: "MOBILE ACCESSORIES",
          items: [{ label: "Cables" }],
        },
      ],
      [
        {
          label: "PC ESSENTIALS",
          items: [
            { label: "Laptop Stands" },
            { label: "Keyboards" },
            { label: "Pads" },
            { label: "Mice" },
            { label: "Hubs And Card Readers" },
            { label: "PC Audio" },
            { label: "Presenters" },
            { label: "Security Cables" },
            { label: "Photo Papers" },
            { label: "Webcams" },
          ],
        },
      ],
      [
        {
          label: "BAGS AND CASES",
          items: [
            { label: "Backpacks" },
            { label: "Ladies Bag" },
            { label: "Laptop Sleeves" },
            { label: "Notebook Cases" },
          ],
        },
      ],
      [
        {
          label: "MOUNTS",
          items: [
            { label: "TV Mounts" },
            { label: "Projector Mounts" },
            { label: "Monitor Mounts" },
          ],
        },
        {
          label: "PROJECTION SCREENS",
          items: [
            { label: "Tripod Screen" },
            { label: "Wall Screens" },
            { label: "Electric Screens" },
          ],
        },
      ],
    ],
  },
  {
    label: "BUSINESS",
    icon: "pi pi-clock",
    items: [
      [
        {
          label: "BUSINESS",
          items: [
            { label: "Premium Keyboards" },
            { label: "Ergonomic Mice" },
            { label: "Headset" },
            { label: "Backpacks" },
          ],
        },
      ],
    ],
  },
  {
    label: "WHERE TO BUY",
    icon: "pi pi-clock",
  },
  {
    label: "SUPPORT",
    icon: "pi pi-clock",
  },
  {
    label: "WEBINARS",
    icon: "pi pi-clock",
  },
  {
    label: "BLOG",
    icon: "pi pi-clock",
  },
  {
    label: "CATALOG",
    icon: "pi pi-clock",
  },
]);
</script>

<style>
#input {
  background-color: #e7e7e7;
  outline: none;
  padding: 0.4rem 0.5rem;
  font-size: 0.9rem;
  color: rgba(0, 0, 0, 0.5);
}
.card {
  padding-top: 5px;
  display: flex;
  justify-content: space-evenly;
}

.options {
  margin: 20px 0;
  padding: 10px;
}

.options .p-megamenu {
  padding: 10px;
}
</style>
