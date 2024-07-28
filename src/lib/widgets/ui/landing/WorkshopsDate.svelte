<section class="section-workshops">
  <div class="left-block">
    <div class="full-moon-image-container">
      <img src="images/workshop.svg" loading="lazy"  alt="" class="image-23">
      <div class="large-stat-text centered white absolute">7</div>
    </div>
    <div>
      <a  href="/" class="share-button-container light w-inline-block">
        <div class="div-block-20">
          <div class="cta-text">Rejestracja</div>
          <div>
            <img src="images/share-icn.svg" loading="lazy" alt="">
          </div>
        </div>
      </a>
    </div>
  </div>
  <div class="calendar">
    <img src="images/month-Cal-Container.png" loading="lazy" sizes="(max-width: 479px) 83vw, 25vw"  alt="" class="calendar-img">
    <div  class="workshops-date">
      <div class="text-block-2 text-2xl">Następny warsztat</div>
      <div class="leading-none text-block-3 ">Podczas Agile.nights </div>
      <div class="text-subtext">Spokojnie, nie możemy podać dokładnych dat dla Agile.nights.</div>
    </div>
  </div>
</section>

<div class="bottom-element">
  <div class="div-block-11">
    <div class="div-block-29">
      <img src="images/redhalfcircle.png" loading="lazy" alt="" class="bottom-element-img">
      <img src="images/orange-halfcircle.png" loading="lazy" sizes="(max-width: 479px) 67vw, 33vw"  alt="" class="image-5">
    </div>
  </div>
</div>


<!--
  -->
<style>

.calendar-img {
  width: 25vw;
  position: absolute;
}


.bottom-element {
  width: 100%;
  position: relative;
}
.bottom-element-img {
  z-index: 4;
  width: 16.66vw;
  perspective-origin: 50% 100%;
  transform-origin: 50% 100%;
  align-self: flex-end;
  margin-left: 8.33vw;
  position: absolute;
  top: auto;
  bottom: 0%;
  left: 0%;
  right: 0%;
}
.full-moon-image-container {
  width: 41.66vw;
  height: 41.66vw;
  background-color: #1a3541;
  border: 1px solid #e8e5e0;
  justify-content: center;
  align-items: center;
  margin-left: 16.66vw;
  display: flex;
  position: relative;
  overflow: hidden;
}

.section-workshops {
  background-color: #1a3541;
  justify-content: space-between;
  padding-top: 8.33vw;
  padding-right: 8.33vw;
  display: flex;
}
.left-block {
  flex-direction: column;
  align-items: flex-end;
  padding-top: 4vh;
  display: flex;
}

.calendar {
  z-index: 2;
  width: 25vw;
  align-self: baseline;
  position: -webkit-sticky;
  position: sticky;
  top: 8.33vw;
}

.text-block-2 {
  text-align: center;
  padding-top: 5vw;
  font-family: Recifedisplay, sans-serif;
  position: relative;
}
.text-block-3 {
  z-index: 2;
  color: #fff;
  text-align: center;
  padding-top: 4vw;
  padding-bottom: 2vw;
  font-family: Fellix, sans-serif;
  font-size: 4em;
  font-weight: 700;
  position: relative;
}
.div-block-11 {
  background-color: #1a3541;
  justify-content: flex-start;
  align-items: flex-end;
  display: flex;
  position: relative;
  overflow: visible;
}
@media screen and (max-width: 991px) {
  .text-block-2 {
    padding-top: 4vw;
  }
  .text-block-3 {
    padding-top: 4vw;
    padding-bottom: 0;
    font-size: 2em;
  }
}

@media screen and (max-width: 767px) {
  .text-block-2 {
    padding-top: 4vw;
  }
  .text-block-3 {
    line-height: 0.4em;
  }
}


@media screen and (max-width: 479px) {
  .text-block-2 {
    /* padding-bottom: 25%; */
    font-size: 1.2em;
  }
  .text-block-3 {
    font-size: 3.4em;
  }
    .calendar {
    width: 83.34vw;
    position: relative;
    top: auto;
  }
  .left-block {
    width: 100%;
    margin-left: auto;
    margin-right: 8.33vw;
    padding-top: 10vh;
    padding-bottom: 6vh;
  }
  .workshops-date {
    position: absolute;
    top: 11%;
    bottom: auto;
    left: 0%;
    right: 0%;
  }
  .section-workshops {
    flex-direction: column-reverse;
    padding-top: 6vh;
    padding-bottom: 10vh;
    padding-left: 8.33vw;
  }
  .full-moon-image-container {
    width: 83.34vw;
    height: auto;
  }
  .calendar-img {
    width: 83.34vw;
    position: relative;
  }
}
</style>
