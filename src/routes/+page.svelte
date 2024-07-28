<script>
	// import {  } from '$lib/shared';
	// BoardgameMoments,
  import { Nav, Hero, HeroBottomLine, ReadyToGetStarted, PreBenefits, Benefits, WorkshopsDate, Team, Runline, Stats, Faq, Footer, AgileFans,  FeaturesSlider, TextDividerSection } from '$lib/widgets';
  // import {  } from '$lib/entities'
</script>


<svelte:head>
  <title>Kanbanism</title>
</svelte:head>


<!-- <a href="#hero" class="back-to-top w-inline-block">
  <img src="images/65ba6362203ce87e9a201c54_back-to-top.png" loading="lazy" alt="" class="backtotop-icn">
</a> -->

<Nav />

<div>
  <section class=''>
    <Hero />

    <HeroBottomLine />
  </section>

  <Runline />

  <a name="about" />
  <Stats />


  <TextDividerSection text={`Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.`}/>

  <!-- <div data-w-id="4135c12b-01a3-70f0-1811-80bcb585e498" class="section-3-wrapper">
    <div data-w-id="d1efd859-7c28-46ba-e404-298265c18b6c" class="large-body-block">Shift by shift <span class="image-span span-wrapper"></span>, nurses prove that <span class="span-wrapper">multitasking</span> is their cardio. </div>
    <div class="hide-this">
      <div class="large-body-block">
        <img src="images/65ba6362203ce87e9a201be5_Large-Purple-Triangle2.png" loading="lazy" sizes="100vw" srcset="images/65ba6362203ce87e9a201be5_Large-Purple-Triangle2-p-500.png 500w, images/65ba6362203ce87e9a201be5_Large-Purple-Triangle2-p-800.png 800w, images/65ba6362203ce87e9a201be5_Large-Purple-Triangle2-p-1080.png 1080w, images/65ba6362203ce87e9a201be5_Large-Purple-Triangle2-p-1600.png 1600w, images/65ba6362203ce87e9a201be5_Large-Purple-Triangle2.png 1835w" alt="" class="span-element is-2">
      </div>
      <div class="large-body-block">multitasking</div>
      <img src="images/65ba6362203ce87e9a201beb_underline-1.png" loading="lazy" alt="" class="span-element is-1">
    </div>
  </div> -->


  <WorkshopsDate />

  <PreBenefits />

  <Benefits />

  <!-- <div class="section-6-wrapper">
    <div class="large-body-block">Every shift, every hour <span class="image-span span-wrapper"></span>, and every moment you’re on the clock makes a <span class="span-wrapper">real</span> difference. </div>
    <div class="hide-this">
      <div class="large-body-block">
        <img src="images/redSquare.png" loading="lazy" alt="" class="span-element is-3">
      </div>
      <div class="large-body-block">
        <span class="span-wrapper">real</span>
      </div>
      <img src="images/65ba6362203ce87e9a201c64_orange-underline.svg" loading="lazy" alt="" class="span-element is-4">
    </div>
  </div> -->

  <TextDividerSection text={`Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.`}/>

  <!-- <div class="section-7-wrapper">
    <div class="div-block-12">
      <div id="streaksContainer" class="streaks-container">
        <img src="images/65ba6362203ce87e9a201c4c_streakgraphic.png" loading="lazy" sizes="(max-width: 479px) 83vw, (max-width: 991px) 41vw, 42vw" srcset="images/65ba6362203ce87e9a201c4c_streakgraphic-p-500.png 500w, images/65ba6362203ce87e9a201c4c_streakgraphic-p-800.png 800w, images/65ba6362203ce87e9a201c4c_streakgraphic.png 1154w" alt="" id="Streaks" class="streaks-image">
        <div id="Holidays-worked" class="large-stat-text centered">5 Days</div>
      </div>
      <div>
        <a id="shareLongestStreak" href="#" class="share-button-container w-inline-block">
          <div class="div-block-20">
            <div class="cta-text">Share</div>
            <div>
              <img src="images/share-icn.svg" loading="lazy" alt="">
            </div>
          </div>
        </a>
      </div>
    </div>
    <img src="images/65ba6362203ce87e9a201be5_Large-Purple-Triangle2.png" loading="lazy" sizes="(max-width: 479px) 100vw, 67vw" srcset="images/65ba6362203ce87e9a201be5_Large-Purple-Triangle2-p-500.png 500w, images/65ba6362203ce87e9a201be5_Large-Purple-Triangle2-p-800.png 800w, images/65ba6362203ce87e9a201be5_Large-Purple-Triangle2-p-1080.png 1080w, images/65ba6362203ce87e9a201be5_Large-Purple-Triangle2-p-1600.png 1600w, images/65ba6362203ce87e9a201be5_Large-Purple-Triangle2.png 1835w" alt="" class="image-7">
  </div> -->


  <!-- <Team /> -->


  <div class="section-8-wrapper">
    <div class="div-block-24">
      <div class="col-1-icon">
        <div class="w-layout-grid day-grid">
          <img src="images/65ba6362203ce87e9a201be6_worksites-Icn.png" loading="lazy" id="w-node-_16d03602-4d7e-e3b8-00db-8a4c148c8f83-9a201bcd" alt="">
          <div id="w-node-_16d03602-4d7e-e3b8-00db-8a4c148c8f84-9a201bcd" class="shape-yellow-square"></div>
        </div>
      </div>
      <div class="col-2-top-day">
        <div class="days-stat-container">
          <div id="worksites-works" class="large-stat-text centered">3</div>
          <div id="WorksitesWorkTextID" class="label-top">Worksites Worked</div>
        </div>
      </div>
    </div>
    <div class="col-4-hospital-name">
      <div class="days-worked-stat-container">
        <div class="label-top">Top Worksite</div>
        <div id="top-worksite" class="medium-text">Good Samaritan Hospital</div>
      </div>
    </div>
  </div>

  <TextDividerSection text={`Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.`}/>

  <ReadyToGetStarted />

  <FeaturesSlider />

  <AgileFans />

  <Faq />

  <Footer />
</div>

<style>

</style>
