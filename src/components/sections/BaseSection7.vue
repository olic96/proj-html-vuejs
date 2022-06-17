<template>
  <section>
      <div class="container">
          <BaseCardTitleSection/>
          <div class="row">
              <div class="col-6">
                  <h4>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</h4>
                  <BaseCardSection7/>
                  <BaseCardSection7/>
              </div>
              <div class="col-6">
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Officia voluptates quod exercitationem ducimus quidem odio </p>
                  <BaseCardSection7/>
                  <BaseCardSection7/>              
              </div>
          </div>
      </div>
  </section>
</template>

<script>
import BaseCardSection7 from '../commons/BaseCardSection7.vue'
import BaseCardTitleSection from '../commons/BaseCardTitleSection.vue'
export default {
    components: { BaseCardTitleSection, BaseCardSection7 },
    name:'BaseSection7',
}
</script>

<style>

</style>