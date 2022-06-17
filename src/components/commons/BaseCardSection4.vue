<template>
  <div class="card my-3">
      <div class="purple">
          <h5>Lorem lorem</h5>
          <p>Lorem </p>
          <div class="sector">
              <div class="mouth">
                  12-24 <br>
                  Mouth olds
              </div>
              <div class="class"></div>
          </div>
      </div>
      <div class="img">
          <img src="../../fable/images/gallery_04.jpg" alt="">
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
    flex-wrap: nowrap;
    color: var(--third-color);
}

.purple {
    background-color: var(--first-color);
}

.col-6 img {
   width: 100%;
}

.sector, h5, p  {
    margin-left: 20px;
    margin-top: 20px ;
}

h5 {
    color: var(--third-color);
}

button {
    border: none;
    background-color: var(--second-color);
    padding: 10px 15px;
    color:  var(--third-color);
}
</style>