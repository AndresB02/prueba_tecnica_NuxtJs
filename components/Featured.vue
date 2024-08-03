<template>
  <!-- principal section -->
  <div class="featured-Section py-20">
    <!-- container -->
    <div class="p-0 container mx-auto sm:px-4">
      <!-- info container -->
      <div class="flex flex-wrap w-full m-auto">
        <!-- information -->
        <div class="m-auto text-center sm:w-2/3 pr-4 pl-4">
          <h5 class="title-featured m-1">Featured</h5>
          <h6 class="subtitle-featured">Blog post</h6>
          <p class="info-featured">Innovations</p>
        </div>
      </div>
      <!-- pincipal section blog post -->
      <div
        class="flex flex-wrap w-full m-auto feature-cards container min-w-lg mx-auto sm:px-4 p-0"
      >
        <!--  -->
        <div
          class="w-full relative flex-grow max-w-full flex-1 px-4-md-4 p-2 px-4"
        >
          <div
            class="relative flex flex-col min-w-0 rounded break-words border bg-white border-1 border-gray-300 mb-2 p-0"
          >
            <img
              src="https://klip-xtreme-frontend.s3.amazonaws.com/media/img/banner-blog-Klip-Big-Audio-Home.jpg"
              class="card-img"
            />
            <div
              class="card-content absolute w-full text-center pb-3 box-info-blog-post"
            >
              <p class="text-center text-white info-blog-post">
                “Big audio” speakers, which one is right for me?
              </p>
              <a
                href="#"
                class="inline-block align-middle text-center select-none border font-normal whitespace-no-wrap leading-normal no-underline m-auto w-1/2 btn-outline-klip rounded-full py-2 px-4 btn-info-blog-post"
                target="_self"
                >Read more</a
              >
            </div>
          </div>
        </div>
        <!--  -->
        <div
          class="w-full relative flex-grow max-w-full flex-1 px-4-md-4 p-2 px-4"
        >
          <div
            class="relative flex flex-col min-w-0 rounded break-words border bg-white border-1 border-gray-300 mb-2 p-0"
          >
            <img
              src="https://klip-xtreme-frontend.s3.amazonaws.com/media/img/banner-blog-Klip-IPX7-home.jpg"
              class="card-img"
            />
            <div
              class="card-content absolute w-full text-center pb-3 box-info-blog-post"
            >
              <p class="text-center text-white info-blog-post">
                IPX7 protection: small subtleties
              </p>
              <a
                href="#"
                class="inline-block align-middle text-center select-none border font-normal whitespace-no-wrap leading-normal no-underline m-auto w-1/2 btn-outline-klip rounded-full py-2 px-4 btn-info-blog-post"
                target="_self"
                >Read more</a
              >
            </div>
          </div>
        </div>
        <!--  -->
        <div
          class="w-full relative flex-grow max-w-full flex-1 px-4-md-4 p-2 px-4"
        >
          <div
            class="relative flex flex-col min-w-0 rounded break-words border bg-white border-1 border-gray-300 mb-2 p-0"
          >
            <img
              src="https://klip-xtreme-frontend.s3.amazonaws.com/media/img/banner-blog-Klip-TWS-home.jpg"
              class="card-img"
            />
            <div
              class="card-content absolute w-full text-center pb-3 box-info-blog-posst"
            >
              <p class="text-center text-white info-blog-post">
                Advantages offered by TWS technology that you shouldn’t ignore
              </p>
              <a
                href="#"
                class="inline-block align-middle text-center select-none border font-normal whitespace-no-wrap leading-normal no-underline m-auto w-1/2 btn-outline-klip rounded-full py-2 px-4 btn-info-blog-post"
                target="_self"
                >Read more</a
              >
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.title-featured {
  text-align: center;
  font-weight: 100;
  color: #7a7a7a;
  font-size: 5vmax;
  line-height: 0.8;
}
.subtitle-featured {
  font-size: 2.5em;
  color: #454545;
  text-transform: none;
  padding-bottom: 7px;
  font-weight: 300;
  margin-bottom: -10px;
}
.box-info-blog-post {
  position: absolute;
  top: 72%;
}
.box-info-blog-posst {
  position: absolute;
  top: 65%;
}
.feature-cards {
  width: 100%;
  max-width: 1140px;
}
.info-featured {
  color: #7de140;
  font-weight: 300;
}
.info-blog-post {
  font-weight: 200;
  padding-bottom: 12px;
}
.btn-info-blog-post {
  color: #7de140;
  border-color: #7de140;
  font-weight: 400;
  font-size: 1rem;
}
.btn-info-blog-post:hover {
  color: white;
  background-color: #7de140;
}
</style>
