<template>
  <main>
    <BaseHero/>
    <BaseSection1/>
    <BaseSection2/>
  </main>
</template>

<script>
import BaseSection1 from '../sections/BaseSection1.vue'
import BaseHero from '../sections/BaseHero.vue'
import BaseSection2 from '../sections/BaseSection2.vue'

export default {
  components: { BaseHero, BaseSection1, BaseSection2 },
  name: 'BaseMain',
}
</script>

<style>

</style>