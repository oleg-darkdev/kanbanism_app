<script>
  const data = ['', '']
</script>

<section class="section section--slider">
  <div class="slider__content">
    <div class="swiper swiper--reviews">
      <div class="swiper-wrapper">

        <!-- {#each data as ar} -->
        <div class="swiper-slide slide--reviews">
          <div class="slide__col col--1">
            <img src="images/61976daacf885c1405737de2_slide_01.jpg" loading="lazy" sizes="(max-width: 767px) 100vw, 32vw"  alt="" class="slide__img">
          </div>
          <div class="slide__col col--2">
            <div class="slide__txt-wrap">
              <h2 class="heading--size-50 mod--slider">Capture, Proof &amp; <br>convert customers </h2>
              <p class="slide__desc">Easily embed customer registration forms, login boxes, and user authentication options for your applications. Prove an unknown user’s real identity, in real-time, during your onboarding or KYC process. Can embed forms from third-party websites and services including NetSuite, Oracle PeopleSoft and many more.Identify real people with pre-built connectors.</p>
            </div>
          </div>
        </div>
        <!-- {/each} -->

      </div>
    </div>
    <div class="slide__nav col--3">
      <div class="slide__block mod--1">
        <div  class=" swiper--reviews-numb">
          <div class="swiper-wrapper vert">
            <div class="swiper-slide slide--reviews-numb">
              <div class="slide__numb">01.</div>
            </div>
            <div class="swiper-slide slide--reviews-numb">
              <div class="slide__numb">02.</div>
            </div>
            <div class="swiper-slide slide--reviews-numb">
              <div class="slide__numb">03.</div>
            </div>
          </div>
        </div>
      </div>
      <div class="slide__block-grid">
        <div class="slide__block mod--2">
          <img src="images/619f839041180c08126da896_slide_ico-01.svg" loading="lazy" alt="" class="slide__img-cone">
        </div>
        <div class="slide__block mod--2 mod--dark"></div>
        <div class="slide__block mod--2"></div>
        <div  class="slide__block mod--2 mod--next">
          <div class="slide__next"></div>
        </div>
      </div>
    </div>
  </div>
</section>


<style>
.slide__block-grid {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  height: 50%;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-flex: 1;
  -webkit-flex: 1;
  -ms-flex: 1;
  flex: 1;
}

  .slide__nav.col--3 {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 17vw;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 auto;
  -ms-flex: 0 0 auto;
  flex: 0 0 auto;
}


.slide__numb {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  height: 100%;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}
  .swiper.swiper--reviews {
  overflow: hidden;
  width: auto;
  margin-bottom: -1px;
  -webkit-box-flex: 1;
  -webkit-flex: 1;
  -ms-flex: 1;
  flex: 1;
}
.swiper.swiper--reviews-numb {
  overflow: hidden;
  width: 100%;
  height: 100px;
}
.swiper-wrapper {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 100%;
  height: 100%;
  -webkit-box-orient: horizontal;
  -webkit-box-direction: normal;
  -webkit-flex-direction: row;
  -ms-flex-direction: row;
  flex-direction: row;
  -webkit-box-align: stretch;
  -webkit-align-items: stretch;
  -ms-flex-align: stretch;
  align-items: stretch;
}
.swiper-wrapper.vert {
  display: block;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
}
.swiper-slide {
  position: relative;
  display: block;
  height: auto;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: stretch;
  -webkit-align-items: stretch;
  -ms-flex-align: stretch;
  align-items: stretch;
}
.swiper-slide.slide--reviews {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 100%;
  height: auto;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 auto;
  -ms-flex: 0 0 auto;
  flex: 0 0 auto;
}
.swiper-slide.slide--reviews-numb {
  width: 100%;
  height: 100%;
}

.section.section--slider {
  z-index: 0;
  overflow: hidden;
  padding: 0;
}
.slider__content {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 100%;
}

@media screen and (max-width: 991px) {
  .slide__block-grid {
    height: auto;
  }

  .slide__nav.col--3 {
    width: 100%;
    min-height: 17vw;
  }
  .slide__col.col--1 {
    height: auto;
  }
  .slide__col.col--2 {
    padding: 55px 20px 55px 40px;
  }
  .slide__block.mod--1 {
    width: 20%;
    height: auto;
  }
  .slide__block.mod--2 {
    width: 25%;
    height: auto;
  }
  .slide__txt-wrap {
    margin-left: 0;
  }
  .slide__img-cone {
    width: 40%;
  }
  .slide__next {
    opacity: 1;
  }
  .section.section--slider {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }
.swiper.swiper--reviews {
    width: 100%;
    margin-bottom: 0;
  }
    .slider__content {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }
}


@media screen and (max-width: 767px) {
  .swiper-slide {
    width: 100%;
  }
  .swiper-slide.slide--reviews {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
  }
  .slide__nav.col--3 {
    min-height: auto;
  }
}

@media screen and (max-width: 479px) {
  .slider__content {
    display: block;
  }
  .swiper-slide,
  .swiper.swiper--reviews,
  .swiper.swiper--reviews-numb {
    width: 100%;
  }

  .slide__desc {
    font-size: 14px;
    line-height: 1.6em;
  }
  .slide__img-cone {
    width: auto;
  }
}
</style>
