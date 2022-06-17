<template>
  <section class="my-5">
      <div class="container">
          <BaseCardTitleSection/>
          <BaseCardSection1/>
      </div>
  </section>
</template>

<script>
import BaseCardSection1 from '../commons/BaseCardSection1.vue'
import BaseCardTitleSection from '../commons/BaseCardTitleSection.vue'
export default {
  components: { BaseCardSection1, BaseCardTitleSection },
    name:'BaseSection1',
}
</script>

<style lang='scss' scoped>

</style>