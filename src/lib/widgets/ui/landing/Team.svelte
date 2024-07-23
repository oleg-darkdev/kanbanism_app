<script>
  const teamArr = [
    '',
    '',
    '',
  ]
</script>

<section class="section">
  <div class="content">
    <h2 class="heading--size-50">Nasz zespół</h2>
    <div class="argument__columns mx-auto">
      <div class="argument__col col--left">
        <img src="images/team/oleg_medvedev.png" loading="lazy" width="528" sizes="(max-width: 991px) 100vw, 528px" alt="Oleg Medvedev as speaker photo" class="argument__img mod--first">
        <div class="argument__title">Oleg Medvedev</div>
        <div class="argument__desc">Author / Front end developer</div>
      </div>
      <div class="argument__col col--right">

        <div class="argument__card mod--mob">
          <img src="images/team/oleg_medvedev.png" loading="lazy" alt="Oleg Medvedev as speaker photo" class="argument__img">
          <div class="argument__title">Oleg Medvedev</div>
          <div class="argument__desc">Author / Front end developer</div>
          <img src="images/619d0fc10ade224d902fa4fc_arrgument-zeros.svg" loading="lazy" alt="" class="argument__card-zeros">
        </div>

        <div class="argument__card">
          <img src="images/619e208b9d632766ef59aeec_argument_person-02.jpg" loading="lazy" alt="" class="argument__img">
          <div class="argument__title">Lorem Ipsum</div>
          <div class="argument__desc">Lorem Ipsum is simply dummy</div>
        </div>

        <!-- <div class="argument__card">
          <div class="argument__cube">
            <div  class="argument__cube-front">
              <div class="argument__cube-side mod--1"></div>
              <div class="argument__cube-side mod--2"></div>
              <div class="argument__cube-side mod--3"></div>
              <div class="argument__cube-title">Write your <br>comment </div>
            </div>
          </div>
        </div> -->
      </div>
    </div>
  </div>
</section>



<style>
.argument__columns {
  display: flex;
}
.argument__col.col--right {
  display: flex;
  padding-left: 16px;
  -webkit-flex-wrap: wrap;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -webkit-box-flex: 1;
  -webkit-flex: 1;
  -ms-flex: 1;
  flex: 1;
}
.argument__col.col--left {
  position: relative;
}
.argument__card {
  width: 33.333333333333336%;
  margin-bottom: 33px;
  padding-left: 16px;
}
.argument__card.mod--mob {
  display: none;
}
.argument__img {
  margin-bottom: 15px;
  border: 1px solid #111;
  /* -webkit-filter: grayscale(100%);
  filter: grayscale(100%); */
  -webkit-transition: 0.2s;
  transition: 0.2s;
}
.argument__img:hover {
  -webkit-filter: none;
  filter: none;
}
.argument__img.mod--first {
  border-width: 0;
}
.argument__title {
  margin-bottom: 5px;
  font-weight: 700;
  text-transform: uppercase;
}
.argument__cube {
  height: 100%;
  max-height: 240px;
  padding-right: 20px;
  padding-bottom: 20px;
}
.argument__cube.hide {
  display: none;
}
.argument__cube-front {
  position: relative;
  bottom: 0;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  width: 100%;
  height: 100%;
  padding-bottom: 24px;
  padding-left: 24px;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
  -webkit-flex-direction: column;
  -ms-flex-direction: column;
  flex-direction: column;
  -webkit-box-pack: end;
  -webkit-justify-content: flex-end;
  -ms-flex-pack: end;
  justify-content: flex-end;
  border: 1px solid #000;
  background-image: url("../images/619673a1e6479d9ad39c673c_ico_arrow-top-right.svg"),
    url("../images/61967d0bf77afe1c2a0ddae3_cube-dots.svg"),
    -webkit-gradient(linear, left top, right top, from(#20c8bf), to(#f8e07c));
  background-image: url("../images/619673a1e6479d9ad39c673c_ico_arrow-top-right.svg"),
    url("../images/61967d0bf77afe1c2a0ddae3_cube-dots.svg"),
    linear-gradient(90deg, #20c8bf, #f8e07c);
  background-position: 89% 11%, 24px 24px, 0 0;
  background-size: auto, auto, auto;
  background-repeat: no-repeat, no-repeat, repeat;
  -webkit-transition: 0.2s;
  transition: 0.2s;
  cursor: pointer;
}
.argument__cube-front.active {
  bottom: -20px;
}
.argument__cube-side {
  z-index: -1;
  border: 1px solid #000;
  background-color: #f5f5f5;
  -webkit-transition: 0.2s;
  transition: 0.2s;
}
.argument__cube-side.mod--3 {
  position: absolute;
  left: 9px;
  top: auto;
  right: -11px;
  bottom: -20px;
  height: 20px;
  -webkit-transform: skew(45deg, 0deg);
  -ms-transform: skew(45deg, 0deg);
  transform: skew(45deg, 0deg);
}
.argument__cube-side.mod--3.active {
  bottom: 20px;
}
.argument__cube-side.mod--2 {
  position: absolute;
  left: auto;
  top: 9px;
  right: -20px;
  bottom: -10px;
  z-index: 0;
  width: 20px;
  -webkit-transform: skew(0deg, 45deg);
  -ms-transform: skew(0deg, 45deg);
  transform: skew(0deg, 45deg);
}
.argument__cube-side.mod--2.active {
  top: -10px;
  bottom: 9px;
  -webkit-transform: skew(0deg, -45deg);
  -ms-transform: skew(0deg, -45deg);
  transform: skew(0deg, -45deg);
}
.argument__cube-side.mod--1 {
  position: absolute;
  left: 9px;
  top: 20px;
  right: -10px;
  bottom: auto;
  height: 20px;
  -webkit-transform: skew(-45deg, 0deg);
  -ms-transform: skew(-45deg, 0deg);
  transform: skew(-45deg, 0deg);
}
.argument__cube-side.mod--1.active {
  top: -20px;
}
.argument__cube-title {
  margin-bottom: 5px;
  color: #111;
  font-size: 18px;
  line-height: 1em;
  font-weight: 700;
}

@media screen and (max-width: 991px) {
  .argument__card-zeros {
    position: absolute;
    left: auto;
    top: 0;
    right: 10px;
    bottom: auto;
    z-index: 2;
  }

  .argument__columns {
    margin-right: -10px;
    margin-left: -10px;
  }

  .argument__col.col--left {
    display: none;
  }

  .argument__col.col--right {
    padding-left: 0;
  }

  .argument__card {
    padding-right: 10px;
    padding-left: 10px;
  }
  .argument__card.mod--mob {
    position: relative;
    display: block;
  }
  .argument__cube {
    max-height: none;
    padding-bottom: 80px;
  }
}

@media screen and (max-width: 767px) {
  .argument__col.col--right {
    -webkit-box-pack: center;
    -webkit-justify-content: center;
    -ms-flex-pack: center;
    justify-content: center;
  }


  .argument__card {
    min-width: 180px;
    margin-bottom: 32px;
    -webkit-box-flex: 1;
    -webkit-flex: 1;
    -ms-flex: 1;
    flex: 1;
  }
  .argument__cube-front {
    padding-bottom: 15px;
    padding-left: 14px;
    background-position: 90% 7%, 14px 12px, 0 0;
    background-size: auto, 36px, auto;
  }
}
@media screen and (max-width: 479px) {
  .argument__title {
    margin-bottom: 2px;
    font-size: 14px;
  }
  .argument__card {
    width: 50%;
    min-width: auto;
    -webkit-box-flex: 0;
    -webkit-flex: 0 auto;
    -ms-flex: 0 auto;
    flex: 0 auto;
  }

  .argument__cube {
    padding-right: 15px;
    padding-bottom: 71px;
  }
  .argument__cube-front.active {
    bottom: -14px;
  }
  .argument__cube-side.mod--3 {
    left: 6px;
    right: -7px;
    bottom: -15px;
    height: 15px;
  }
  .argument__cube-side.mod--2 {
    top: 7px;
    right: -15px;
    bottom: -7px;
    width: 15px;
  }
  .argument__cube-side.mod--2.active {
    top: -7px;
    bottom: 7px;
  }
  .argument__cube-side.mod--1 {
    right: -7px;
    height: 15px;
  }
  .argument__cube-side.mod--1.active {
    left: 7px;
    top: -15px;
    right: -7px;
  }
}
</style>
