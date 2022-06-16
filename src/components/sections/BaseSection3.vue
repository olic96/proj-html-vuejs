<template>
  <section class="section_3">
    <BaseCardSection3/>
  </section>
</template>

<script>
import BaseCardSection3 from '../commons/BaseCardSection3.vue'

export default {
  components: { BaseCardSection3 },
    name:'BaseSection3',
}
</script>

<style lang="scss" scoped>
    .section_3 {
        height: 400px;
        background-image:url("../../fable/images/parallax_01.jpg");
        background-size: cover;
    }
</style>