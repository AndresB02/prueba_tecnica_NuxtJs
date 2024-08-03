<template>
  <section
    class="home-lg-section mosaic relative mx-auto sm:px-1 max-w-full min-w-md"
  >
    <div
      class="flex flex-wrap w-full lg:w-5/6 pr-4 pl-4 lg:mx-1/6 p-0 lg:items-start m-auto"
    >
      <div
        class="box-kruiser bg-klipxtreme mosaic-text md:w-2/5 pr-4 pl-4 w-full"
      >
        <div class="text-center text-white">
          <p class="m-0 text-4xl">KRUISER</p>
          <p>Designed for today’s professionals</p>
          <p class="text-justify">
            KlipXtreme offers an exclusive design for modern professionals with
            its Kruiser backpack that redefines the premium accessories market
            by merging portability with security elements that provide
            everything that you need for your journey.
          </p>
        </div>
        <div class="flex justify-center w-full text-gray-900 text-center mb-5">
          <div class="button-readme-container w-full text-center">
            <a
              href="#"
              class="inline-block align-middle text-center select-none border font-normal whitespace-no-wrap leading-normal no-underline text-green-500 border-green-500 hover:bg-green-500 hover:text-whit hover:green-600 rounded-full py-2 px-4 w-full btn-learn"
              >Learn more</a
            >
          </div>
        </div>
      </div>
      <div class="p-0 md:w-3/5 pr-4 pl-4 w-full">
        <img
          src="https://klip-xtreme-frontend.s3.amazonaws.com/media/img/Banner-producto-home-KNB-901.jpg"
          alt="Banner-producto-home-KNB-901.jpg"
          width="100%"
        />
      </div>
    </div>
    <div class="flex flex-wrap w-full product-flex m-auto p-0 container-images">
      <div
        class="bg-gray-100 lg:ml-4 p-0 m-auto lg:m-0 md:w-1/2 pr-4 pl-4 lg:w-1/3 w-4/5 container.images"
      >
        <a href="#" class="text-normal text-gray-900 text-decoration-none"
          ><figure class="text-center p-6 m-0">
            <img
              src="https://klip-xtreme-frontend.s3.amazonaws.com/media/img/KBK-530S_BannerWeb_destacado3_BIL_JD_VF.png"
              alt="KBK-530S_BannerWeb_destacado3_BIL_JD_VF.png"
              width="100%"
              class="m-auto"
            />
          </figure>
          <div class="boxGris-content text-center">
            <h3>Transcend Wireless</h3>
            <h6>Wireless ergonomic premium keyboard</h6>
          </div></a
        >
      </div>
      <div
        class="bg-gray-100 lg:ml-4 p-0 m-auto lg:m-0 md:w-1/2 pr-4 pl-4 lg:w-1/3 w-4/5"
      >
        <a href="#" class="text-normal text-gray-900 text-decoration-none"
          ><figure class="text-center p-6 m-0">
            <img
              src="https://klip-xtreme-frontend.s3.amazonaws.com/media/img/KCH-905_BannerWeb_destacado3_BIL_JD_VF.png"
              width="100%"
              class="m-auto"
            />
          </figure>
          <div class="boxGris-content text-center">
            <h3>CrystalCom Pro</h3>
            <h6>
              Monoaural wireless headset.
              <span style="color: rgb(51, 51, 51)">Bluetooth</span
              ><sup>®</sup>-compatible wireless technology with magnetic
              charging base
            </h6>
          </div></a
        >
      </div>
    </div>
  </section>
</template>

<style>
.home-lg-section {
  width: 100%;
  max-width: 1140px;
  height: 100%;
  max-height: 1000px;
  padding-top: 100px;
}
.box-kruiser {
  background-color: #7de140;
  padding: 50px;
}
.container-images {
  position: relative;
  top: -320px;
}
.btn-learn {
  background-color: transparent;
  font-weight: 300;
  margin-top: 20px;
}
.btn-learn:hover {
  background-color: #28a745;
  color: white;
}
</style>
