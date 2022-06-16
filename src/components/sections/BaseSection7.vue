<template>
  <section>
      <div class="container">
          <BaseCardTitleSection/>
          <div class="row">
              <div class="col-6">
                  <h4></h4>
                  <!-- v-for card -->
              </div>
              <div class="col-6">
                  <p></p>
                  <!-- v-for card -->
              </div>
          </div>
      </div>
  </section>
</template>

<script>
import BaseCardTitleSection from '../commons/BaseCardTitleSection.vue'
export default {
    components: { BaseCardTitleSection },
    name:'BaseSection7',
}
</script>

<style>

</style>