<section class="section-5-container">
    <div class="section-5-wrapper">
      <div class="section-5-top flex">
        <div class="col-1-icon">
          <div class="w-layout-grid day-grid">
            <img src="images/heart-Icn.png" loading="lazy"  alt="">
            <div class="shape-orange-square">
              <img src="images/blueSquare.png" loading="lazy" alt="" class="w-full">
            </div>
          </div>
        </div>
        <div class="col-2-top-day">
          <div  class="days-stat-container">
            <div class="label-top">Lorem Ipsum</div>
            <div  class="day-text">Lorem</div>
          </div>
        </div>
      </div>
      <div class="div-block-23">
        <div>
          <div class="col-3-days-worked">
            <div  class="">
              <div class="large-stat-text days">0000</div>
              <div class="label-top">
                <span class="text-span-9">Lorem Ipsum</span>
              </div>
            </div>
          </div>
          <div class="green-box"></div>
        </div>
        <div class="w-layout-grid grid section5">
          <div  class="shape-blue-square">
            <img src="images/blueSquare.png" loading="lazy" width="121" alt="">
          </div>
          <div  class="div-block-5"></div>
          <div  class="div-block-5">
            <img src="images/yellowsquare.svg" loading="lazy" width="61" alt="">
          </div>
          <div class="div-block-5"></div>
          <div class="shape-green-square">
            <img src="images/greenquartercircle.png" loading="lazy" width="121.5" alt="">
          </div>
          <div  class="div-block-5"></div>
          <div  class="div-block-5"></div>
          <div class="shape-purple-square">
            <img src="images/redSquare.png" loading="lazy" width="121.5" alt="">
          </div>
          <div  class="div-block-5"></div>
        </div>
      </div>
    </div>
    <div class="section-5-holidays-wrapper">
      <div class="col-2-blank">
        <img src="images/large-Purple-Triangle.png" loading="lazy" sizes="33vw"  alt="">
      </div>
      <div class="col-2-holidays-worked">
        <div class="">
          <div  class="large-stat-text centered">0000</div>
          <div class="label-top">
            <span  class="text-span-10">Lorem </span> Ipsum
          </div>
        </div>
      </div>
    </div>
</section>


<style>

.col-2-holidays-worked {
  width: 33.33vw;
  height: 33.33vw;
  background-color: #fff;
  border: 0.5px solid #000;
  justify-content: center;
  align-items: center;
  display: flex;
}
.section-5-holidays-wrapper {
  justify-content: flex-start;
  align-items: stretch;
  margin-left: 16.66vw;
  display: flex;
}

  .section-5-container {
  z-index: 4;
  position: relative;
}

.section-5-wrapper {
  z-index: 5;
  justify-content: flex-start;
  align-items: flex-start;
  display: flex;
  position: relative;
}
@media screen and (max-width: 479px) {
  .section-5-wrapper {
    flex-direction: column;
    justify-content: flex-end;
  }
    .section-5-top {
    width: 100%;
    align-items: flex-end;
    display: flex;
  }
  .div-block-23 {
    width: 100%;
    height: auto;
    aspect-ratio: 2/1;
    justify-content: space-between;
    align-items: flex-start;
    display: flex;
  }
  .col-2-holidays-worked {
    width: 66.66vw;
    height: 66.66vw;
  }

  .section-5-holidays-wrapper {
    flex-direction: row;
    margin-left: auto;
  }
}


</style>
