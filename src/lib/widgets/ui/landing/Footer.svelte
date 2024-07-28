<footer class="footer">
    <div class="footer-row-1">
        <div class="medium-text-copy">
        <strong>Podziel się swoimi statystykami!</strong>
        </div>
        <div class="small-text">Tag <span class="text-span-5">@agile.fans</span> na Instagramie.</div>
    </div>
    <div class="footer-right-block-wrapper">
        <div class="footer-right-block">
            <!-- logo -->
            <!-- <img src="/images/logo.svg" loading="lazy" alt="" class="footer-logo"> -->
        </div>

        <div class="social-containter">
            <!-- social icons -->
            <a href="/" target="_blank" class="social-icon w-inline-block">
                <img src="images/instagram.png" loading="lazy" alt="instagram logo">
            </a>

        </div>
    </div>
</footer>


<style>
.social-containter {
  justify-content: flex-end;
  padding-left: 2vw;
  display: flex;
}
.footer {
  height: auto;
  background-color: #ff9461;
  padding-top: 4vh;
  padding-left: 8vw;
  padding-right: 8vw;
}
.footer-row-1 {
  padding-bottom: 4vh;
}
.footer-right-block-wrapper {
  width: 100%;
  border-top: 0.5px solid #1a3541;
  border-bottom: 0.5px #000;
  justify-content: space-between;
  padding-top: 4vh;
  padding-bottom: 2.5vh;
  display: flex;
}
.footer-right-block {
  width: 15vw;
}
.social-icon {
  width: 2vw;
  margin-left: 2vw;
}

@media screen and (max-width: 479px) {
  .footer-right-block {
    width: 25vw;
    align-self: flex-start;
  }
  .social-containter {
    margin-bottom: 2.5vh;
  }
  .social-icon {
    width: 7vw;
    margin-left: 2.5vw;
    margin-right: 1vw;
  }
}
@media screen and (max-width: 767px) {
  .social-icon {
    width: 5vw;
  }
}


</style>
