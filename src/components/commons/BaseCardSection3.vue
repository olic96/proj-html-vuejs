<template>
  <div class="container">
      <div class="row">
          <div class="col-3">
              <div class="number">507</div>
              <h5>Lorem</h5>
              <p>Lorem ipsum dolor sit amet consectetur.</p>
          </div>
          <div class="col-3">
              <div class="number">507</div>
              <h5>Lorem</h5>
              <p>Lorem ipsum dolor sit amet consectetur.</p>
          </div>
          <div class="col-3">
              <div class="number">507</div>
              <h5>Lorem</h5>
              <p>Lorem ipsum dolor sit amet consectetur.</p>
          </div>
          <div class="col-3">
              <div class="number">507</div>
              <h5>Lorem</h5>
              <p>Lorem ipsum dolor sit amet consectetur.</p>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name:'BaseCardSection3',
}
</script>

<style lang="scss" scoped>
.container {
    text-align: center;
    color:var(--third-color) ;
}

h5 {
    color:var(--third-color) ;
}

.number {
    padding: 30px;
    border: 1px solid var(--third-color);
    border-radius: 50%;
    font-size: 50px;
}
</style>