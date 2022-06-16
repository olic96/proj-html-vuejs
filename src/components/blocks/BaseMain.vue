<template>
  <main>
    <BaseHero/>
    <BaseSection1/>
    <BaseSection2/>
    <BaseSection3/>
  </main>
</template>

<script>
import BaseSection1 from '../sections/BaseSection1.vue'
import BaseHero from '../sections/BaseHero.vue'
import BaseSection2 from '../sections/BaseSection2.vue'
import BaseSection3 from '../sections/BaseSection3.vue'


export default {
  components: { BaseHero, BaseSection1, BaseSection2, BaseSection3 },
  name: 'BaseMain',
}
</script>

<style>

</style>