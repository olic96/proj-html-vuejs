<template>
  <section>
    <div class="container">
      <BaseCardTitleSection/>
      <div class="row">
          <div class="col-6">
              <h4></h4>
              <!-- v-for create card-->
          </div>
          <div class="col-6">
              <p></p>
              <!-- v-for create card -->
          </div>
      </div>
    </div>
  </section>
</template>

<script>
import BaseCardTitleSection from '../commons/BaseCardTitleSection.vue'
export default {
    components: { BaseCardTitleSection },
    name:'BaseSection4',
}
</script>

<style>

</style>