<template>
  <div class="hero_bottom">
      <div class="container">
          <div>
              Lorem ipsum dolor sit amet consectetur, adipisicing elit.
          </div>
          <div>
              <button>
                  LEARN MORE
              </button>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name:'BaseCardHeroBottom',
}
</script>
    
<style lang='scss' scoped>
    .container {
        display: flex;
        justify-content: space-between;
    }
    .hero_bottom {
        height: 110px;
        background-image: url("../../fable/images/pattern.png");
    }
</style>