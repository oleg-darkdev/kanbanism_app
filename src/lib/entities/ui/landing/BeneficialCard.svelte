<script>
  export let benefits;
</script>

<div class="benefits-card">
    <div class="flex w-full">
        <div class="div-block-32">
        <img src="images/checkmark.png" loading="lazy" alt="" class="image-20">
        </div>
        <div class="benefit-container">
        <div class="holiday-text">{benefits}</div>
        </div>
    </div>
</div>


<style>
.benefits-card {
  padding-left: 16.66vw;
}
@media screen and (max-width: 991px) {
  .benefits-card {
    padding-left: 0;
  }
}
.benefit-container {
  width: 58.33vw;
  height: 8.33vw;
  border: 0.5px solid #000;
  align-self: auto;
  align-items: center;
  padding-left: 4.16vw;
  display: flex;
}

.div-block-32 {
  width: 8.33vw;
  height: 8.33vw;
  border: 0.5px solid #000;
  justify-content: center;
  align-self: center;
  align-items: center;
  display: flex;
}

@media screen and (max-width: 479px) {
  .div-block-32 {
    width: 16.66vw;
    height: 16.66vw;
  }
  .benefit-container {
    width: 100%;
    height: 16.66vw;
  }
}
</style>
