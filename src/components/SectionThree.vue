<template>
    <section class="section">
        <div class="section__top">
            <h2>Our Work</h2>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quae nostrum ex.</p>
        </div>
        <div class="section__img">
            <img src="../assets/img/case-study-gallery-3-1-200x150.jpg" alt="">
            <img src="../assets/img/case-study-gallery-2-200x150.jpg" alt="">
            <img src="../assets/img/case-study-gallery-1-1-200x150.jpg" alt="">
            <img src="../assets/img/case-study-gallery-4-1-200x150.jpg" alt="">
            <img src="../assets/img/case-study-gallery-5-1-200x150.jpg" alt="">
            <img src="../assets/img/case-study-gallery-6-1-200x150.jpg" alt="">
            
        </div>
        <div class="section__btn">
            <button class="btn">VIEW OUR WORK</button>
        </div>
    </section>
</template>

<script>
export default {
    name: 'SectionThree'
}
</script>

<style lang='scss' scoped>

@import '../assets/style/mixins.scss';

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
                margin: 0px 0px 40px 0px;
            }
        }

        &__img {

            max-width: var(--container-medium);
            justify-content: center;
            min-height: 300px;
            display: flex;
            flex-wrap: wrap;

            img {
                width: calc(100% / 3 - 30px);
                border: solid 5px transparent;
                margin: 5px;
                cursor: pointer;
            }

            img:hover {
                border-color: var(--orange);
            }
        }

        &__btn {
            display: flex;
            justify-content: center;

            .btn {
                margin: 30px 0px 80px 0px;
                @include button-orange-bis;
            }

            .btn:hover {
                @include button-white;
            }
        }
    }
</style>