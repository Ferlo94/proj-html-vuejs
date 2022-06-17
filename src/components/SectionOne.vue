<template>
    <section class="section">
        <div class="section__top">
            <h2>Meet The New Agency SEO Temple <br> From The Avada Team</h2>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing eli, <br> distinctio. quae quibusdam corporis.</p>
        </div>
        <div class="section__mid">
            <div class="card-section-1">
                <i class="fa-solid fa-road icon"></i>
                <h3>Establish Goals</h3>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Molesti  adipis. Lorem ipsum dolor sit amet consectetur  </p>
            </div>
            <div class="card-section-1">
                <i class="fa-solid fa-video icon"></i>
                <h3>Work Whith a Team</h3>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Molesti  adipis. Lorem ipsum dolor sit amet consectetur  </p>
            </div>
            <div class="card-section-1">
                <i class="fa-solid fa-droplet icon"></i>
                <h3>Get Results</h3>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Molesti  adipis. Lorem ipsum dolor sit amet consectetur  </p>
            </div>
        </div>
        <div class="section__bottom">
            <img src="../assets/img/agency-seo-desk-front-1200x570.jpg" alt="">
        </div>

    </section>
</template>

<script>
export default {
    name: 'SectionOne'
}
</script>

<style lang='scss' scoped>

@import '../assets/style/mixins.scss';

    .section {
        min-height: 650px;
        background: #f7f8fa;

        &__top {
            @include container-x-small;
            display: flex;
            flex-direction: column;
            justify-content: center;
            text-align: center;

            h2 {
                font-size: 30px;
                margin: 90px 0px 25px 0px;
            }

            p {
                font-weight: 500;
                color: var(--grey);
                
            }

        }

        &__mid {
            @include container-medium;
            display: flex;
            justify-content: center;
            margin-top: 30px;

            .card-section-1 {
                background: white;
                height: 280px;
                width: calc(100% / 3);
                display: flex;
                flex-direction: column;
                justify-content: center;
                align-items: center;
                text-align: center;
                padding: 20px;
                margin: 10px;
                cursor: pointer;
                border: solid 2px transparent;

                .icon {
                    color: var(--orange);
                    font-size: 30px;

                }

                h3 {
                    margin: 25px 0px;
                    font-size: 25px;
                }

                p {
                    font-size: 16px;
                    font-weight: 500;
                }
            }

            .card-section-1:hover {
                border: 2px solid black;
            }
        }

        &__bottom {
            display: flex;
            justify-content: center;
        }
    }
</style>