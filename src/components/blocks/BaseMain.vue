<template>
  <main>
    <BaseHero/>
    <BaseSection1/>
    <BaseSection2/>
    <BaseSection3/>
    <BaseSection4/>
    <BaseSection5/>
    <BaseSection6/>
  </main>
</template>

<script>
import BaseSection1 from '../sections/BaseSection1.vue'
import BaseHero from '../sections/BaseHero.vue'
import BaseSection2 from '../sections/BaseSection2.vue'
import BaseSection3 from '../sections/BaseSection3.vue'
import BaseSection4 from '../sections/BaseSection4.vue'
import BaseSection5 from '../sections/BaseSection5.vue'
import BaseSection6 from '../sections/BaseSection6.vue'


export default {
  components: { BaseHero, BaseSection1, BaseSection2, BaseSection3, BaseSection4, BaseSection5, BaseSection6 },
  name: 'BaseMain',
}
</script>

<style>
 
</style>