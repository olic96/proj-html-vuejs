<template>
  <section class="my-5">
      <div class="section_6_top">
        <img src="../../fable/images/gallery_01.jpg">
        <img src="../../fable/images/gallery_02.jpg">
        <img src="../../fable/images/gallery_03.jpg">
        <img src="../../fable/images/gallery_04.jpg">
        </div>
      <BaseCardHeroBottom/>
  </section>
</template>

<script>
import BaseCardHeroBottom from '../commons/BaseCardHeroBottom.vue'
export default {
  components: { BaseCardHeroBottom },
  name:'BaseSection6',  
}
</script>

<style lang="scss" scoped>
    .section_6_top {
        display: flex;
        flex-wrap: nowrap;
    }

    img {
        height: 200px;
        width: 300px;
    }
</style>