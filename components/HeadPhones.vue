<template>
  <div class="home-lg-section bannerPair container min-w-md mx-auto sm:px-4">
    <div class="flex flex-wrap w-full m-auto container-headphones-speakers">
      <!-- section headphones -->
      <div class="m-auto px-0 xl:px-4 sm:w-1/2 pr-4 pl-4 w-full">
        <article class="w-full m-auto">
          <figure class="text-center flex flex-col">
            <div class="text-left col-12 pt-4">
              <h2 class="title-headphones">HEADPHONES</h2>
              <p class="subtitle-headphones text-gray-700">
                FOR THE BEST AUDIO FANS ONLY
              </p>
            </div>
            <div class="bannerPair-img position-relative">
              <img
                src="https://klip-xtreme-frontend.s3.amazonaws.com/media/img/Banner-Audio.jpg"
                alt="HEADPHONES"
              />
              <div class="bannerPair-button w-full text-right">
                <a href="#" class="btn-headphones"> Find out more </a>
              </div>
            </div>
          </figure>
        </article>
      </div>
      <!-- section speakers -->
      <div class="m-auto px-0 xl:px-4 sm:w-1/2 pr-4 pl-4 w-full">
        <article class="w-full m-auto">
          <figure class="text-center flex flex-col sm:flex-col-reverse">
            <div class="text-left w-full pt-4">
              <div class="bannerPair-img relative">
                <img
                  src="https://klip-xtreme-frontend.s3.amazonaws.com/media/img/Banner-Speakers.jpg"
                  alt="SPEAKERS"
                />
                <div class="bannerPair-button w-full text-right">
                  <a href="#" class="btn-speakers"> Find out more </a>
                </div>
              </div>
              <h2 class="title-speakers">SPEAKERS</h2>
              <p class="subtitle-speakers text-muted">
                #KLIPXTREME, YOUR SOUND!
              </p>
            </div>
          </figure>
        </article>
      </div>
    </div>
  </div>
</template>

<style>
.container-headphones-speakers {
  width: 100%;
  max-width: 1140px;
}
.title-headphones,
.title-speakers {
  color: #dbdde0;
  font-size: 3vw;
}
.subtitle-headphones,
.subtitle-speakers {
  text-align: left;
  font-weight: 400;
  color: #6c757d;
  font-size: 1vmax;
  line-height: 1.6;
  letter-spacing: 5px;
}
.btn-headphones,
.btn-speakers {
  position: relative;
  top: -50px;
  left: -35px;
  color: #7de140;
  border: 1px solid #7de140;
  width: 100%;
  max-width: 33.333333%;
  padding: 0.375rem 0.75rem;
  border-radius: 50rem;
  font-size: 1.2rem;
}
.btn-headphones:hover,
.btn-speakers:hover {
  color: white;
  background-color: #7de140;
}
</style>
