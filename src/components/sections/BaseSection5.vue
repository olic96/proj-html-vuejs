<template>
  <section class="section_5 my-5">
      <div class="container">
         <div class="row">
              <div class="col-6">
              <h4>Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis, optio maxime laudantium suscipit quo deserunt eum animi unde?</h4>
              <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dignissimos delectus dolorem repudiandae illum.</p>
              <ul>
                  <li>
                      <span><img src="../../fable/images/style_1.png"></span>
                      <span>lorem</span>
                  </li>
                  <li>
                      <span><img src="../../fable/images/style_1.png"></span>
                      <span>lorem</span>
                  </li>
                  <li>
                      <span><img src="../../fable/images/style_1.png"></span>
                      <span>lorem</span>
                  </li>
                  <li>
                      <span><img src="../../fable/images/style_1.png"></span>
                      <span>lorem</span>
                  </li>
                  <li>
                      <span><img src="../../fable/images/style_1.png"></span>
                      <span>lorem</span>
                  </li>
              </ul>
          </div>
          <div class="col-6 col_left">
              <div class="row">
                  <div class="col-6">
                      <div class="background">
                          <img src="../../fable/images/toy.png">
                      </div>
                      <h5>Lorem</h5>
                      <p>Lorem ipsum dolor sit amet.</p>
                  </div>
                  <div class="col-6">
                      <div class="background">
                          <img src="../../fable/images/toy.png">
                      </div>
                      <h5>Lorem</h5>
                      <p>Lorem ipsum dolor sit amet.</p>
                  </div>
              </div>
              <div class="row">
                  <div class="col-6">
                      <div class="background">
                          <img src="../../fable/images/toy.png">
                      </div>
                      <h5>Lorem</h5>
                      <p>Lorem ipsum dolor sit amet.</p>
                  </div>
                  <div class="col-6">
                      <div class="background">
                          <img src="../../fable/images/toy.png">
                      </div>
                      <h5>Lorem</h5>
                      <p>Lorem ipsum dolor sit amet.</p>
                  </div>
              </div>
          </div>
         </div>
      </div>
  </section>
</template>

<script>
export default {
    name:'BaseSection5',
}
</script>

<style lang="scss" scoped>
    .section_5 {
        background-color: var(--third-color);
    }

    .col-6, .col-6 h4, .col-6 p {
        margin: 20px 0;
    }

    ul li {
        display: block;
    }

    span img {
        margin-right: 10px;
    }

    .col_left {
        text-align: center;
    }

    .col_left img {
        margin-bottom: 15px;
    }
</style>