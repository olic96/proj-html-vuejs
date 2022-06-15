<template>
  <main>
    <BaseHero/>
    <BaseCardSection1/>
  </main>
</template>

<script>
import BaseCardSection1 from '../commons/BaseCardSection1.vue'
import BaseHero from '../sections/BaseHero.vue'

export default {
  components: { BaseHero, BaseCardSection1 },
  name: 'BaseMain',
}
</script>

<style>

</style>