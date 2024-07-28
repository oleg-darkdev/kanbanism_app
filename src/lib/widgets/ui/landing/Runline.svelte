<script>
  //
  const tags = [
    'Kanbanism', 'Kanban', 'agile',
  ]
</script>

<section class=" section--runline py-6">
  <div class="runtext__content">
    <div class="runtext__block">
      <!-- {#each tags as tag} <span>{tag}</span> {/each} -->
      <!-- 💚 kanban -->
      <div class="runtext__txt"><span>Uruchom swój kanban</span> </div>
      <!-- <img src="images/61af8ba2bc3b4b1cc88768d7_star_green.png" width="25" alt="" class="runtext__img-star"> -->
    </div>
  </div>
</section>


<style>

.slide__col.col--1 {
  width: 32vw;
  height: 100%;
  border-right: 1px solid #000;
  border-bottom: 1px solid #000;
}
.slide__col.col--2 {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  padding-top: 80px;
  padding-bottom: 80px;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-flex: 1;
  -webkit-flex: 1;
  -ms-flex: 1;
  flex: 1;
  border-bottom: 1px solid #000;
}
.slide__desc {
  margin-bottom: 0;
  color: rgba(45, 45, 45, 0.8);
  line-height: 1.8em;
}
.slide__block {
  position: relative;
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
  -webkit-justify-content: center;
  -ms-flex-pack: center;
  justify-content: center;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  border-bottom: 1px solid #000;
  border-left: 1px solid #000;
}
.slide__block.mod--1 {
  width: 100%;
  height: 50%;
  color: #f5f5f5;
  font-size: 95px;
  font-weight: 500;
  text-shadow: -1px 0 0 #000, 0 1px 0 #000, 1px 0 0 #000, 0 -1px 0 #000;
}
.slide__block.mod--2 {
  width: 50%;
  height: 50%;
}
.slide__block.mod--2.mod--next {
  overflow: hidden;
  background-image: url("/images/61976fb6df78962a5fbb70ed_ico_arrow-slide.svg");
  background-position: 50% 50%;
  background-size: auto;
  background-repeat: no-repeat;
  cursor: pointer;
}
.slide__block.mod--2.mod--dark {
  background-image: url("/images/619e77b859a298e13ab5b5a4_solutions_bg-02.jpg");
  background-position: 50% 50%;
  background-size: cover;
  background-repeat: no-repeat;
}
.slide__img {
  display: block;
  width: 100%;
  height: 100%;
  -o-object-fit: cover;
  object-fit: cover;
}
.slide__txt-wrap {
  width: 100%;
  max-width: 512px;
  margin-right: auto;
  margin-left: auto;
}
.slide__img-cone {
  position: relative;
  width: 40%;
}


.heading--size-50.mod--slider {
  margin-bottom: 30px;
}
.slide__next {
  position: absolute;
  left: 0;
  top: 0;
  right: 0;
  bottom: 0;
  margin: -1px;
  background-image: url("/images/61976fb6df78962a5fbb70ed_ico_arrow-slide.svg"),
    -webkit-gradient(linear, left top, right top, from(#20c8bf), to(#f8e07c));
  background-image: url("/images/61976fb6df78962a5fbb70ed_ico_arrow-slide.svg"),
    linear-gradient(90deg, #20c8bf, #f8e07c);
  background-position: 50% 50%, 0 0;
  background-size: auto, auto;
  background-repeat: no-repeat, repeat;
  opacity: 0;
  -webkit-transition: 0.2s;
  transition: 0.2s;
}
.slide__next:hover {
  opacity: 1;
}



.section.section--runline {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  overflow: hidden;
  height: 154px;

  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  border-top: 1px solid #000;
  border-bottom: 1px solid #000;
}

.runtext__txt {
  margin-top: -2px;
  padding-right: 40px;
  padding-left: 40px;
  color: #f5f5f5;
  font-size: 72.5px;
  line-height: 1em;
  font-weight: 700;
  text-transform: uppercase;
  text-shadow: -1px 0 0 #000, 0 1px 0 #000, 1px 0 0 #000, 0 -1px 0 #000;
}
.runtext__content {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}
.runtext__img-star {
  position: relative;
}
.runtext__block {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
  -webkit-box-flex: 0;
  -webkit-flex: 0 0 auto;
  -ms-flex: 0 0 auto;
  flex: 0 0 auto;
}

@media screen and (max-width: 767px) {
  .runtext__txt {
    padding-right: 20px;
    padding-left: 20px;
    font-size: 60px;
  }

  .slide__col.col--1 {
    width: 100%;
    height: 240px;
    border-right-width: 0;
  }
  .slide__col.col--2 {
    padding-left: 20px;
  }
  .slide__block.mod--1 {
    width: 50%;
    height: 50vw;
    border-left-width: 0;
  }
  .slide__block.mod--2 {
    width: 50%;
    height: 50%;
  }
  .slide__txt-wrap {
    max-width: 100%;
  }
}
</style>
