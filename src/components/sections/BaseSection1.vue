<template>
  <section>
      <div class="container">
          <div class="col-12">
              <h1>Lorem ipsum</h1>
              <p><small>Lorem ipsum dolor sit amet</small></p>
              <img src="../../fable/images/header_divider.png">
          </div>
          <BaseCardSection1/>
      </div>
  </section>
</template>

<script>
import BaseCardSection1 from '../commons/BaseCardSection1.vue'
export default {
  components: { BaseCardSection1 },
    name:'BaseSection1',
}
</script>

<style lang='scss' scoped>
    .container {
        text-align: center;
    }
</style>