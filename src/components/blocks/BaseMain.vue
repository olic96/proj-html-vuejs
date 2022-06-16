<template>
  <main>
    <BaseHero/>
    <BaseSection1/>
    <BaseSection2/>
    <BaseSection3/>
    <BaseSection4/>
    <BaseSection5/>
    <BaseSection6/>
    <BaseSection7/>
    <BaseSection8/>
    <BaseSection9/>
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
import BaseSection7 from '../sections/BaseSection7.vue'
import BaseSection8 from '../sections/BaseSection8.vue'
import BaseSection9 from '../sections/BaseSection9.vue'


export default {
  components: { BaseHero, BaseSection1, BaseSection2, BaseSection3, BaseSection4, BaseSection5, BaseSection6, BaseSection7, BaseSection8, BaseSection9 },
  name: 'BaseMain',
}
</script>

<style>
 
</style>