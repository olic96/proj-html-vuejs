<template>
  <header class="container">
    <img class="logo" src="../../fable/images/logo.png" alt="logo">
    <BaseCardNav/>
  </header>
</template>

<script>
import BaseCardNav from '../commons/BaseCardNav.vue';
export default {
    components: { BaseCardNav },
    name: 'BaseHeader',
    
}
</script>

<style lang="scss" scoped>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 110px;
}

.logo {
  height: 100%;
}
</style>