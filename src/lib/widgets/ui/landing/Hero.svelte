<script>
  import { ShareBtn } from '$lib/shared';
</script>


<section class="hero-section h-[70vh]">
  <div class="hero-left">
    <div class="div-block">
      <div class="side-note">Praca nad wydaniem nowej wersji gry.</div>
    </div>
    <div  class="card-container">
      <div  class="text-block-6">
        <span class="text-span-6">Kanbanism</span>
        <br>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
      </div>
      <div class="card-image-cta">
        <div style="" class="card-image-container">
          <img src="images/hero.png" loading="lazy" sizes="(max-width: 479px) 95vw, (max-width: 767px) 67vw, (max-width: 991px) 33vw, 27vw"  alt="">
        </div>
      </div>
    </div>
  </div>
  <div  class="hero-bottom-row-mobile">
    <!-- <div class="div-block-25">
      <a href="#Overview-Mobile" class="scroll-button-container-mobile w-inline-block">
        <img src="images/65ba6362203ce87e9a201be9_karat-placeholder.png" loading="lazy" width="97" alt="" class="image-10">
      </a>
      <a href="#twoColSection" class="scroll-button-container w-inline-block">
        <img src="images/65ba6362203ce87e9a201be9_karat-placeholder.png" loading="lazy" width="97" alt="" class="image-10">
      </a>
      <div class="scroll-button-container staticon">
        <img src="images/65ba6362203ce87e9a201bea_Stat-Icon-Noleftblock.png" loading="lazy" alt="" class="image-11">
      </div>
      <div class="grid-container"></div>
    </div> -->


    <ShareBtn />


  </div>

  <div class="hero-right">
    <div class="title-name-container">
      <div class="user-name">Lorem Ipsum is simply dummy</div>
      <!-- <img src="images/65ba6362203ce87e9a201bdc_2023-Modular-Mark.png" loading="eager" sizes="100vw" alt="" class="image-24"> -->
    </div>
    <div class="subhead-container">
      <p  class="body-block-small">
        <span class="text-span-2">Lorem Ipsum is simply dummy text of the printing and typesetting industry. </span>
        Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
      </p>
    </div>
    <img src="images/65ba6362203ce87e9a201c41_action%20lines.png" loading="eager"  alt="" class="image-13">
  </div>
</section>


<style>

.hero-right {
  width: 50vw;
  height: auto;
  justify-content: center;
  padding-top: 6vh;
  display: block;
  position: relative;
}

  @media screen and (max-width: 991px) {
  .hero-right {
    display: none;
  }
/* .hero-right {
    padding-left: 8.33vw;
  } */
}

@media screen and (max-width: 767px) {
  /* .hero-right {
    width: 83.34vw;
    margin-bottom: 10vh;
    margin-left: 8.33vw;
    margin-right: 8.33vw;
    padding-top: 8vh;
  } */
}

@media screen and (max-width: 479px) {
  .hero-right {
    margin-bottom: 8.33vh;
    padding-left: 0;
  }
}
</style>
