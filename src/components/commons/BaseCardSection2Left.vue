<template>
  <div class="col-6">
        <div class="flex">
        <div class="orange">Overview</div>
        <div class="trasparent">OurMission</div>
        </div>
        <h4>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</h4>
        <div class="flex">
            <img class="icon" src="../../fable/images/clock.png">
            <div>
            <h5>Lorem</h5>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.!</p>
            </div>
        </div>
        <div class="flex">
            <img class="icon" src="../../fable/images/school.png">
            <div>
            <h5>Lorem</h5>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit..</p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name:'BaseCardSection2Left'
}
</script>

<style lang="scss" scoped>
 .icon {
        height: 100%;
        margin-right: 30px;
        margin-top: 20px;
    }

    .flex {
        display: flex;
    }

    .orange {
        color: var(--third-color);
        padding: 10px 15px;
        background: var(--second-color);
        cursor: pointer;
    }

    .trasparent {
        padding: 10px 15px;
        background: var(--third-color);
        cursor: pointer;
    }
</style>