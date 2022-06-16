<template>
    <section class="section">
        <div class="section__top">

        </div>
        <div class="section__bottom">

        </div>
    </section>
</template>

<script>
export default {
    name: 'SectionTwo'
}
</script>

<style lang= 'scss' scoped>

    .section {
        
        min-height: 200px;
        display: flex;
        flex-direction: column;
        
        &__top {
            height: 650px;
            background-image: url(../assets/img/pattern_background.png);
            background-color: #051642;
            background-repeat: no-repeat;
            background-size: cover;
            background-position: center;
        }
    }

</style>