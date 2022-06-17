<template>
  <section class="section_3">
      <div class="container">
          <div class="row">
              <BaseCardSection2Left/>
              <BaseCardSection2Right/>
          </div>
      </div>
  </section>
</template>

<script>
import BaseCardSection2Left from '../commons/BaseCardSection2Left.vue'
import BaseCardSection2Right from '../commons/BaseCardSection2Right.vue'

export default {
    components:{ BaseCardSection2Left, BaseCardSection2Right },
    name:'BaseSection2',
}
</script>

<style lang="scss" scoped>
    .section_3 {
        background-color: var(--third-color);
    }
</style>