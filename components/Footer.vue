<template>
  <footer class="w-full bg-white border-t pt-2 sm:pt-6 pb-5 sm:pb-4">
    <div
      class="flex flex-wrap w-full md:w-4/5 pr-4 pl-4 xl:w-2/3 justify-center m-auto"
    >
      <!-- first part -->
      <div
        class="py-2 sm:py-4 text-center sm:text-left each-col sm:w-1/3 pr-4 pl-4 w-full"
      >
        <img
          src="../assets/images/logo.png"
          alt="Logo de Klip Xtreme"
          width="160px"
        />
        <ul class="nav footer-nav flex-column">
          <li class="p-0 text-center sm:text-left">
            <a href="#" class="inline-block py-2 px-4 no-underline">Blog</a>
          </li>
          <li class="p-0 text-center sm:text-left">
            <a href="#" class="inline-block py-2 px-4 no-underline">Support</a>
          </li>
          <li class="p-0 text-center sm:text-left">
            <a href="#" class="inline-block py-2 px-4 no-underline">Catalog</a>
          </li>
          <li class="p-0 text-center sm:text-left">
            <a href="#" class="inline-block py-2 px-4 no-underline"
              >Privacy Policy</a
            >
          </li>
          <li class="p-0 text-center sm:text-left">
            <a href="#" class="inline-block py-2 px-4 no-underline"
              >Where To Buy</a
            >
          </li>
          <li class="p-0 text-center sm:text-left">
            <a href="#" class="inline-block py-2 px-4 no-underline">Webinars</a>
          </li>
          <li class="p-0 text-center sm:text-left">
            <a href="#" class="inline-block py-2 px-4 no-underline">Warranty</a>
          </li>
        </ul>
      </div>
      <!-- second part -->
      <div class="py-2 sm:py-4 each-col sm:w-1/3 pr-4 pl-4 md:w-1/4 w-full">
        <h3 class="text-center sm:text-left text-3xl">About Us</h3>
        <ul class="flex flex-wrap list-none pl-0 mb-0 footer-flex flex-col">
          <li class="p-0 text-center sm:text-left">
            <a href="#" class="inline-block py-2 px-4 no-underline"
              >Our company</a
            >
          </li>
        </ul>
        <h3 class="text-center sm:text-left text-3xl">Support</h3>
        <ul class="flex flex-wrap list-none pl-0 mb-0 footer-flex flex-col">
          <li class="p-0 text-center sm:text-left">
            <a href="#" class="inline-block py-2 px-4 no-underline"
              >Contact us</a
            >
          </li>
          <li class="p-0 text-center sm:text-left">
            <a href="#" class="inline-block py-2 px-4 no-underline">FAQs</a>
          </li>
        </ul>
      </div>
      <!-- third part -->
      <div class="sm:w-3/5 pr-4 pl-4 md:w-2/5 sm:mx-2/5 offset-md-0 w-full">
        <div class="hidden md:block">
          <div class="w-full flex justify-center md:justify-start">
            <p class="flex flex-col mb-0 md:mb-2 text-center">
              <a href="#" class="m-0"
                ><font-awesome-icon
                  :icon="['far', 'comment-dots']"
                  size="2xl"
                  style="color: #7de140" /></a
              ><small>Chat</small>
            </p>
            <p class="ml-3 flex flex-col mb-0 md:mb-2 text-center">
              <a href="#" class="m-0"
                ><font-awesome-icon
                  icon="fa-regular fa-envelope"
                  size="2xl"
                  style="color: #7de140" /></a
              ><small>Mail</small>
            </p>
          </div>
        </div>
        <!-- fourth part -->
        <div class="w-fit pd-0 m-0 mt-3 md:mt-2">
          <div
            class="whitespace-no-wrap flex flex-wrap justify-between sm:block"
          >
            <label for="#" class="hidden sm:inline">Follow us on:</label>
            <div class="hidden sm:inline-block">
              <a
                href="https://www.facebook.com/klipxtreme/"
                target="_blank"
                class="pl-3"
                ><font-awesome-icon
                  :icon="['fab', 'facebook-f']"
                  size="lg"
                  style="color: #7de140"
              /></a>
              <a
                href="https://www.instagram.com/klipxtreme"
                target="_blank"
                class="pl-3"
                ><font-awesome-icon
                  :icon="['fab', 'instagram']"
                  size="lg"
                  style="color: #7de140"
              /></a>
              <a
                href="https://twitter.com/klipxtreme"
                target="_blank"
                class="pl-3"
                ><font-awesome-icon
                  :icon="['fab', 'x-twitter']"
                  size="lg"
                  style="color: #7de140"
              /></a>
              <a
                href="https://www.youtube.com/user/KlipXtremeLA"
                target="_blank"
                class="pl-3"
                ><font-awesome-icon
                  :icon="['fab', 'youtube']"
                  size="lg"
                  style="color: #7de140"
              /></a>
              <a
                href="https://www.tiktok.com/@klipxtreme_oficial?_t=8aTyYXT1Byg&amp;_r=1"
                target="_blank"
                class="pl-3"
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
  </footer>
</template>

<style scoped>
footer {
  background: white;
  color: black;
  text-align: center;
  padding-top: 2rem;
  padding-bottom: 1rem;
  border-top: 1px solid #dee2e6;
}
footer .container {
  display: grid;
  grid-template-columns: 400px 400px 400px;
  align-items: center;
  justify-content: center;
  box-sizing: border-box;
}
#logo-footer {
  width: 50%;
}
.container .container-options-footer {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  line-height: 2;
}
.container .container-options-footer ul {
  list-style: none;
}
</style>
