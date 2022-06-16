<template>
  <div class="hero_top">
      <img class="img_1" src="../../fable/images/slider_slide3_img2.png">
      <img class="img_2" src="../../fable/images/slider_slide3_img3.png">
  </div>
</template>

<script>
export default {
    name:'BaseCardHeroTop',
}
</script>

<style lang="scss" scoped>
    .hero_top {
        position: relative;
        height: 400px;
        background-image: url("../../fable/images/slider_slide3_background.png");
        background-size: contain;   
    }

    .img_1, .img_2{
        position: absolute;
    }

    .img_1 {
        height: 100px;
        margin-top: 250px;
        margin-left: 650px;
    }

    .img_2 {
        height: 70px;
        margin-top: 280px;
        margin-left: 1250px;
    }
</style>