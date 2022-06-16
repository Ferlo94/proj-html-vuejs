<template>
    <section class="section">
        <div class="section__top">
            <h2>Our News</h2>
            <p>Soluta eos eaque numquam. Ipsam perferendis sit, bo quasi ex rem distinctio.</p>
        </div>
        <div class="section__mid">
            <img src="../assets/img/related-service-2-320x202.jpg" alt="">
            <img src="../assets/img/related-service-4-320x202.jpg" alt="">
            <img src="../assets/img/blog-post-6-320x202.jpg" alt="">
        </div>
        <div class="section__bottom">

        </div>
    </section>
</template>

<script>
export default {
    name: 'SectionFive'
}
</script>

<style lang='scss' scoped>

@import '../assets/style/mixins.scss';

.section {
    min-height: 600px;
    background: white;
    text-align: center;

    &__top {
        @include container-xx-small;
        display: flex;
        flex-direction: column;
        align-items: center;
        
        h2 {
            margin: 60px 0px 20px 0px;
        }
    }

    &__mid {
        @include container-medium;
        display: flex;
        justify-content: center;

        img {
            width: calc(100% / 3);
            padding: 10px;
        }
    }
}

</style>