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
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Molesti t consectetur, adipis. </p>
            </div>
        </div>
        <div class="section__bottom">

        </div>

    </section>
</template>

<script>
export default {
    name: 'SectionOne'
}
</script>

<style lang='scss' scoped>
    .section {
        height: 650px;
        background: #f7f8fa;

        &__top {
            display: flex;
            flex-direction: column;
            justify-content: center;
            max-width: var(--container-x-small);
            margin: auto;
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
            display: flex;
            max-width: var(--container-medium);

            .card-section-1 {
                background: white;
                height: 180px;
                width: 220px;
                display: flex;
                flex-direction: column;
                justify-content: center;
                align-items: center;
                text-align: center;
                padding: 20px;

                .icon {
                    color: var(--orange);
                    font-size: 20px;

                }

                h3 {
                    margin: 10px 0px;
                }

                p {
                    font-size: 12px;
                }
            }
        }
    }
</style>