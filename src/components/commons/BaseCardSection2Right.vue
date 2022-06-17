<template>
   <div class="col-6">
        <div class="row">
           <div class="col-6">
               <img class="img_col" src="../../fable/images/gallery_01.jpg">
            </div> 
        </div>

        <div class="row">
            <div class="col-4"><img src="../../fable/images/gallery_07-690x506.jpg"></div>
            <div class="col-4"><img src="../../fable/images/gallery_01.jpg"></div>
            <div class="col-4"><img src="../../fable/images/gallery_08-690x506.jpg"></div>
        </div>
    </div>
</template>

<script>
export default {
name:'BaseCardSection2Right'
}
</script>

<style lang="scss" scoped>

.col-4 img, .col-6 img {
    max-width: 100%;
}

</style>