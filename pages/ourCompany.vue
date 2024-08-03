<template>
  <div>
    <Header />
    <div>
      <div>
        <img
          class="x-image"
          src="https://klip-xtreme-frontend.s3.amazonaws.com/media/img/banner-1-About-Us.jpg"
          width="100%"
          alt="imagen del logo de klip xtrem"
        />

        <div class="container-info-klip mx-auto sm:px-4 m-auto">
          <div class="text-separator text-center container mx-auto sm:px-4">
            <h5 data-v-7dcbcf61="" class="home-titlle m-0">Klip Xtreme</h5>
            <h6 data-v-7dcbcf61="" class="home-subtitlle">About Us</h6>
            <!---->
          </div>
          <div
            class="flex flex-wrap md:justify-center pt-2 pb-5 px-4 mb-4 items-center"
          >
            <div class="text-company md:w-full pr-4 pl-4">
              Klip Xtreme&nbsp;is&nbsp;the brand where lifestyle meets
              technology.<br /><br />Specially focused on the expectations of
              the most discriminating consumer, the brand not only delivers
              unequalled performance, but also top-quality with the best user
              experience in every product they buy.<br /><br /><strong
                >KlipXtreme®</strong
              >&nbsp;is a global manufacturer focusing on premium audio devices
              and business products, in addition to a wide range of accessories
              and PC peripheral components.<br /><br />The company is
              strategically headquartered in Miami, Florida, USA. Sales are
              focused on both, the consumer as well as the commercial
              business-to-business (B2B) markets.<br /><br />With a presence in
              over 45 countries, the brand maintains a seamless chain of
              authorized distributors in the United States, Latin America and
              the Caribbean.
            </div>
            <div class="md:w-full pr-4 pl-4 text-companny">
              The transformation of the brand&nbsp;<br /><br />Founded in 2005
              as part of the Accvent Group,&nbsp;<strong>Klip Xtreme®</strong
              >&nbsp;started by designing multimedia accessories, but rapidly
              evolved to meet the ever-growing demand for new, ground-breaking
              and cost-effective products that other brands were failing to
              deliver.<br /><br />Today,&nbsp;<strong>Klip Xtreme®</strong
              >&nbsp;has become the hallmark of innovation by cleverly combining
              its signature style with functionality, while maintaining the
              highest standards of quality, dependability and affordability.<br /><br /><strong
                >Klip Xtreme®</strong
              >&nbsp;has since grown into a much sought-after brand in its
              category, consolidating its presence in five continents so far,
              thanks to its comprehensive portfolio of audio components,
              business and mobile accessories.
            </div>
          </div>
        </div>
        <div>
          <!---->
          <div class="banner-container">
            <div class="support-container">
              <div data-v-28f9fd7a="" class="support-text-container">
                <img
                  class="hd-image"
                  src="https://klip-xtreme-frontend.s3.amazonaws.com/media/img/banner-2-About-Us.jpg"
                  alt="imagen de audifonos"
                />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
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
.x-image {
  width: 100%;
  height: 820px;
}
.hd-image {
  width: 100%;
  height: 600px;
}
.home-titlle {
  color: #7a7a7a;
  font-size: 5vw;
  padding-top: 50px;
}
.home-subtitlle {
  font-size: 2.5em;
  color: #454545;
  text-transform: none;
  padding-bottom: 7px;
  font-weight: 400;
  margin-bottom: -10px;
  padding-bottom: 50px;
}
.text-company {
  font-size: 1rem;
  font-weight: 300;
  line-height: 1.5;
  color: #212529;
  text-align: left;
}
.text-companny {
  font-size: 1rem;
  font-weight: 300;
  line-height: 1.5;
  color: #212529;
  text-align: left;
  padding-bottom: 30px;
}
.container-info-klip {
  width: 100%;
  max-width: 1140px;
}
</style>
