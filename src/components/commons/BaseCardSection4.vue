<template>
  <div class="card">
      <div class="purple">
          <h5>Lorem</h5>
          <p>Lorem</p>
          <div class="sector">
              <div class="mouth">
                  12-24 <br>
                  Mouth olds
              </div>
              <div class="class"></div>
          </div>
      </div>
      <div class="img">
          <button>READ MORE<i class="fa-solid fa-angle-right"></i></button>
      </div>
  </div>
</template>

<script>
export default {
    name:'BaseCardSection4'
}
</script>

<style lang="scss" scoped>
.card {
    display: flex;
}

.purple {
    background-color: var(--first-color);
}

.img {
    position: relative;
    background-image: url("../../fable/images/gallery_04.jpg");
    background-size: cover;
}

button {
    border: none;
    background-color: var(--second-color);
    padding: 10px 15px;
    color:  var(--third-color);
}
</style>