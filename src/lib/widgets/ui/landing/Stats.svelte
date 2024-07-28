<section class="section-stats">
  <div class="section-2-left">
    <div class="col-1-shapes">
      <div class="w-layout-grid grid">
        <div  class="div-block-5"></div>
        <div class="shape-purple-square">
          <img src="images/large-Purple-Triangle.png" loading="lazy" sizes="(max-width: 767px) 50vw, 25vw"  alt="large purple square image" class="image-14">
        </div>
        <div class="div-block-5"></div>
        <div  class="div-block-5"></div>
        <div class="div-block-5"></div>
        <div class="shape-blue-square">
          <img src="images/blueSquare.png" loading="lazy" alt="blue square image">
        </div>
        <div  class="shape-orange-square">
          <img src="images/yellowsquare.svg" loading="lazy" alt="yellow square image">
        </div>
        <div  class="div-block-5"></div>
        <div  class="div-block-5"></div>
      </div>
    </div>

    <div class="col-2-shifts">
      <img src="images/red-halfcircle.png" loading="lazy" alt="red half circle image" class="image-2">
      <div class="shifts-stat-container">
        <div class="large-stat-text">360</div>
        <div class="text-label">
          <span class="text-span-7">minut sesja  </span> rozgrywki
        </div>
      </div>
    </div>
  </div>

  <div  class="section-2-right">
    <div class="col-3-shapes">
      <div class="w-layout-grid grid">
        <div class="div-block-30">
          <img src="images/blueSquare.svg" loading="lazy" alt="big blue square image">
        </div>
        <div  class="div-block-5"></div>
        <div class="div-block-5"></div>
        <div  class="div-block-5"></div>
        <div  class="shape-green-square">
          <img src="images/greenquartercircle.svg" loading="lazy" alt="green circle image">
        </div>
        <div  class="div-block-5"></div>
        <div  class="div-block-5"></div>
        <div class="shape-purple-square">
          <img src="images/redSquare.png" loading="lazy" alt="red square image">
        </div>
        <div class="div-block-5"></div>
      </div>
    </div>

    <div class="col-4-hours">
      <div class="clock-container">
        <div class="clock">
          <div class="minute-hand"></div>
          <div class="hour-hand"></div>
        </div>
        <img src="images/clock-BG.png" loading="lazy" alt="clock image" class="image-3">
      </div>
      <div class="shifts-stat-container">
        <div  class="large-stat-text">120</div>
        <div class="text-label">
          <span class="text-span-8">zadania </span> do szkolenia
        </div>
      </div>
    </div>
  </div>
</section>


<style>
@media screen and (max-width: 479px) {
  .section-stats{
    width: 100vw;
    min-width: 100%;
  }
}

@media screen and (max-width: 767px) {
  .section-stats{
    width: 100vw;
    flex-direction: column-reverse;
  }
}
@media screen and (max-width: 991px) {
  .section-stats{
    width: 100vw;
    border-top-style: solid;
    border-top-width: 0.5px;
  }
}

.section-stats{
  z-index: 3;
  border-top: 1px solid #1a3541;
  justify-content: space-between;
  display: flex;
  position: relative;
  /* top: auto; */
}
</style>
