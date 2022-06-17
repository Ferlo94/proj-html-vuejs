<template>
    <section class="section">
        <div class="section__top">
            <h2>Our News</h2>
            <p>Soluta eos eaque numquam. Ipsam perferendis sit, bo quasi ex rem distinctio.</p>
        </div>
        <div class="section__mid">
            <div class="img-sx">
                <img src="../assets/img/related-service-2-320x202.jpg" alt="">
                <h3>Why You Need A SEO Agency Now</h3>
                <p class="central-p">November 1st 2017</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga quam minima mollitia.</p>
            </div>
            <div class="img-mid">
                <img src="../assets/img/related-service-4-320x202.jpg" alt="">
                <h3>SEO Tips For Your Startup</h3>
                <p class="central-p">November 1st 2017</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga quam minima mollitia.</p>
                </div>
            <div class="img-dx">
                <img src="../assets/img/blog-post-6-320x202.jpg" alt="">
                <h3>Image Optimization For Your Site</h3>
                <p class="central-p">November 1st 2017</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga quam minima mollitia.</p>
                </div>
        </div>
        <div class="section__bottom">
            <button class="btn">GO TO NEWS</button>
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
    background: #f7f8fa;
    text-align: center;

    &__top {
        @include container-xx-small;
        display: flex;
        flex-direction: column;
        align-items: center;
        
        h2 {
            margin: 60px 0px 20px 0px;
        }

        p {
            font-weight: 500;
            color: var(--grey);
            margin-bottom: 50px
        }
    }

    &__mid {
        @include container-medium;
        display: flex;
        justify-content: center;
        flex-wrap: wrap;

        img {
            width: 100%;
            border: solid 5px transparent;
        }

        img:hover {
            border-color: var(--orange);
        }

        .img-sx, .img-mid, .img-dx {
            display: flex;
            flex-direction: column;
            text-align: center;
            width: calc(100% / 3 - 60px);

            h3, p {
                padding: 0px 10px;
            }

            p {
                font-weight: 500;
                color: var(--grey);
            }

            h3 {
                margin-top: .9375rem;
                font-size: 1.0625rem;
                color: var(--orange);
            }

            .central-p {
                margin: 10px 0px 15px 0px;
            }
        }


        
    }

    &__bottom {

        .btn {

            @include button-orange-bis;
            margin: 60px 0px 80px 0px;
        }

        .btn:hover {
                @include button-white;
            }
    }
}

</style>