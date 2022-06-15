<template>
  <section>
      <BaseCardHeroTop/>
      <BaseCardHeroBottom/>
  </section>
</template>

<script>
import BaseCardHeroBottom from '../commons/BaseCardHeroBottom.vue'
import BaseCardHeroTop from '../commons/BaseCardHeroTop.vue'
export default {
  components: { BaseCardHeroTop, BaseCardHeroBottom },
    name:'BaseHero',
}
</script>

<style lang="scss">

</style>