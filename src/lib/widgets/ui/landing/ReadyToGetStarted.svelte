<section class="footer__get group">
  <a  href="/" class="footer__get-link w-inline-block">
    <div class="content">
      <h2 class="heading--size-50 mod--footer ">Gotowy do rozpoczęcia kanban? <span class="heading2__arrow"></span>
      </h2>
    </div>
  </a>
</section>


<style>
  .heading2__arrow {
  position: relative;
  top: auto;
  bottom: auto;
  display: inline-block;
  width: 34px;
  margin-left: 42px;
  background-image: url("/images/ico_arrow-top-right.svg");
  background-position: 50% 50%;
  background-size: contain;
  background-repeat: no-repeat;
  -webkit-filter: brightness(0%) invert(100%);
  filter: brightness(0%) invert(100%);
}


.footer__get-link::after {
  content: " ";
  width: 100%;
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0px;
  background-image: linear-gradient(90deg, #20c8bf, #f8e07c);
  -webkit-transition: -webkit-transform .8s cubic-bezier(0, .5, .5, 1);
  transition: -webkit-transform .8s cubic-bezier(0, .5, .5, 1);
  -o-transition: -o-transform .8s cubic-bezier(0, .5, .5, 1);
  transition: transform .8s cubic-bezier(0, .5, .5, 1);
  transition: transform .8s cubic-bezier(0, .5, .5, 1),
    -webkit-transform .8s cubic-bezier(0, .5, .5, 1),
    -o-transform .8s cubic-bezier(0, .5, .5, 1);
  -webkit-transform: scaleX(0);
  -o-transform: scaleX(0);
  transform: scaleX(0);
  -webkit-transform-origin: 100% 0;
  -o-transform-origin: 100% 0;
  transform-origin: 100% 0;
  z-index: -1;
}

.footer__get-link:hover::after {
  -webkit-transform: scaleX(1);
  -o-transform: scaleX(1);
  transform: scaleX(1);
  -webkit-transform-origin: 0 100%;
  -o-transform-origin: 0 100%;
  transform-origin: 0 100%;
}

.footer__get-link:hover h2 {
  -webkit-filter: invert(95%);
  filter: invert(95%);
}

.footer__get {
  display: block;
  margin-right: -80px;
  margin-left: -80px;
  text-decoration: none;
}
.footer__get-link {
  position: relative;
  z-index: 1;
  display: block;
  padding-top: 40px;
  padding-bottom: 35px;
  text-decoration: none;
}

@media screen and (max-width: 991px) {
  .footer__get {
    margin-right: -20px;
    margin-left: -20px;
  }
}
</style>
