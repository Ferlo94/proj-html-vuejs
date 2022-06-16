<template>
    <section class="section">
        <div class="section__top">
            <h2>Our Work</h2>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quae nostrum ex.</p>
        </div>
        <div class="section__img">
            <img src="../assets/img/case-study-gallery-3-1-200x150.jpg" alt="">
            <img src="../assets/img/case-study-gallery-3-1-200x150.jpg" alt="">
            <img src="../assets/img/case-study-gallery-3-1-200x150.jpg" alt="">
            <img src="../assets/img/case-study-gallery-3-1-200x150.jpg" alt="">
            <img src="../assets/img/case-study-gallery-3-1-200x150.jpg" alt="">
            <img src="../assets/img/case-study-gallery-3-1-200x150.jpg" alt="">
            
        </div>
        <div class="section__btn">

        </div>
    </section>
</template>

<script>
export default {
    name: 'SectionThree'
}
</script>

<style lang='scss' scoped>
    .section {
        min-height: 400px;
        display: flex;
        flex-direction: column;
        align-items: center;
        text-align: center;

        &__top {
            display: flex;
            flex-direction: column;
            align-items: center;
            max-width: var(--container-xx-small);

            h2 {
                margin: 80px 0px 20px 0px;
            }

            p {
                color: var(--grey);
                font-weight: 500;
            }
        }

        &__img {

            max-width: var(--container-medium);
            justify-content: center;
            min-height: 300px;
            display: flex;
            flex-wrap: wrap;


            img {
                width: calc(100% / 3);
                padding: 10px;
            }
        }
    }
</style>