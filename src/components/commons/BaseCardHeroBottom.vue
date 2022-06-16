<template>
  <div class="hero_bottom">
      <div class="container">
          <h2>
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
          </h2>
          <div>
              <button>
                  LEARN MORE <i class="fa-solid fa-angle-right"></i>
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
        align-items: center;
    }
    .hero_bottom {
        height: 110px;
        background-image: url("../../fable/images/pattern.png");
        color: var(--third-color);
    }

    h2, button {
        margin-top: 30px;
    }

    button {
        border: 1px solid var(--third-color);
        color: var(--third-color);
        padding: 10px 15px;
        background: transparent;
    }
</style>