<script>
	import Carousel from 'svelte-carousel'
  import { browser } from '$app/environment'

  const slides = [

    {
      title: 'Lorem Ipsum is simply',
      desc: `It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.`
    },
    {
      title: 'Lorem Ipsum is simply',
      desc: `It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.`
    },
        {
      title: 'Lorem Ipsum is simply',
      desc: `It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.`
    },
        {
      title: 'Lorem Ipsum is simply',
      desc: `It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.`
    },
  ]
</script>

<section class="feature-carousel">

  {#if browser}
    <Carousel
      duration={800}
      autoplay
      timingFunction="linear"
      dots={false}
      arrows={false}
      swiping={true}

      >

  <div class="slider w-slider" >
    <div class="w-slider-mask">
      <!-- slide-2 slide-3 slide-4 slide-5 -->
    <!-- <div slot="prev" on:click={showPrevPage} class="left-arrow w-slider-arrow-left">
      <img src="images/left-arrow.svg" loading="lazy" width="42.5" alt="" class="image-18">
      <div class="text-block-10">Prev</div>
    </div> -->

	{#each slides as slide}
        <div class="slide w-slide">
          <div class="slide-container">
            <div class="copy-container">
              <div class="large-body-block-carousel">
                <strong>{slide.title}</strong>
              </div>
              <div class="body-block-small carousel">
                <strong>
                  <em class="italic-text-2">
                    {slide.desc}
                  </em>
                </strong>
              </div>
              <!-- <a href="/" target="_blank" class="read-more-cta w-inline-block">
                <div class="text-block-9">Lorem Ipsum</div>
              </a> -->
            </div>
            <div class="image-container">
              <img src="images/feature-slider.svg" loading="lazy" sizes="(max-width: 479px) 36vw, 20vw"  alt="">
            </div>
          </div>
        </div>
      {/each}



      <!-- <div slot="next" on:click={showNextPage} class="right-arrow w-slider-arrow-right">
        <div class="text-block-10">Next</div>
        <img src="images/right-arrow.svg" loading="lazy" width="42" alt="" class="image-17">
      </div> -->
      <!-- <div class="slide-nav w-slider-nav w-slider-nav-invert"></div> -->
        </div>
    </div>
    </Carousel>
  {/if}
</section>


<style>
.feature-carousel {
  margin-bottom: 20vh;
  margin-left: 8.66vw;
  padding-right: 8.66vw;
}

@media screen and (max-width: 479px) {
  .feature-carousel {
    margin-left: 4.33vw;
    margin-right: 4.33vw;
    padding-right: 0;
    position: relative;
  }
}
</style>
