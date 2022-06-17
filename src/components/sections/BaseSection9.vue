<template>
  <section class="my-5">
      <div class="container">
          <BaseCardTitleSection/>
          <div class="row">
             <div class="col-4">
                  <BaseSectionCard9/>
             </div>
              <div class="col-4">
                  <BaseSectionCard9/>
             </div>
              <div class="col-4">
                  <BaseSectionCard9/>
             </div>
          </div>
          <button>GO TO BLOG<i class="fa-solid fa-angle-right"></i></button>
      </div>
  </section>
</template>

<script>
import BaseCardTitleSection from '../commons/BaseCardTitleSection.vue'
import BaseSectionCard9 from '../commons/BaseSectionCard9.vue'
export default {
  components: { BaseCardTitleSection, BaseSectionCard9 },
    name:'BaseSection9.',
}
</script>

<style>
    button {
    border: none;
    background-color: var(--second-color);
    padding: 10px 15px;
    color:  var(--third-color);
}
</style>