<template>
  <header class="container">
    <img class="logo" src="../../fable/images/logo.png" alt="logo">
    <!-- <CardNav/> -->
  </header>
</template>

<script>
// import CardNav from './commons/CardNav.vue';
export default {
    name: 'BaseHeader',
    // name: CardNav,
}
</script>

<style lang="scss">
header {
    display: flex;
    height: 110px;
}

.logo {
    height: 100%;
}
</style>