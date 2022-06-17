<template>
  <section>
    <div class="container">
      <BaseCardTitleSection/>
      <div class="row">
          <div class="col-6">
              <h4>Lorem ipsum dolor sit, amet consectetur adipisicing elit.</h4>
              <BaseCardSection4/>
              <BaseCardSection4/>


          </div>
          <div class="col-6">
              <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ipsum eligendi enim recusandae.</p>
              <BaseCardSection4/>
              <BaseCardSection4/>
             
          </div>
      </div>
    </div>
  </section>
</template>

<script>
import BaseCardSection4 from '../commons/BaseCardSection4.vue'
import BaseCardTitleSection from '../commons/BaseCardTitleSection.vue'
export default {
    components: { BaseCardTitleSection, BaseCardSection4 },
    name:'BaseSection4',
}
</script>

<style>

</style>