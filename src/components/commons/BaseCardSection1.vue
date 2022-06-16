<template>
  <div class="row">
      <div class="col-3">
         <div class="orange">
             <img src="../../fable/images/schoolbag_alt.png">
         </div>
         <h5>Lorem</h5>
         <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sequi suscipit laudantium quas sunt qui porro, rerum nisi totam. Sunt dolor consequatur amet, ipsam doloremque tempore optio minus quis cumque totam.</p>
      </div>

      <div class="col-3">
         <div class="purple">
             <img src="../../fable/images/stroller_alt.png">
         </div>
         <h5>Lorem</h5>
         <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sequi suscipit laudantium quas sunt qui porro, rerum nisi totam. Sunt dolor consequatur amet, ipsam doloremque tempore optio minus quis cumque totam.</p>
      </div>

      <div class="col-3">
         <div class="orange">
             <img src="../../fable/images/globe_alt.png">
         </div>
         <h5>Lorem</h5>
         <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sequi suscipit laudantium quas sunt qui porro, rerum nisi totam. Sunt dolor consequatur amet, ipsam doloremque tempore optio minus quis cumque totam.</p>
      </div>

      <div class="col-3">
        <div class="purple">
             <img src="../../fable/images/bell_alt.png">
        </div>
         <h5>Lorem</h5>
         <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sequi suscipit laudantium quas sunt qui porro, rerum nisi totam. Sunt dolor consequatur amet, ipsam doloremque tempore optio minus quis cumque totam.</p>
      </div>
  </div>
</template>

<script>
export default {
    name:'BaseCardSection1',
    
}
</script>

<style lang='scss' scoped>
    .col-3 {
        text-align: center;
    }

    img {
        margin-top: 70px;
    }

    .orange, .purple {
        border-radius: 50%;
        height: 210px;
        
    }

    .orange {
        background-color:var(--second-color) ;
    }

    .purple {
        background-color:var(--first-color);
    }

    h5 {
        color:var(--first-color);
    }
</style>