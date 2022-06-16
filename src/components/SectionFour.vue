<template>
    <section class="section">
        <div class="section__top">
            <h2>Our Plans</h2>
            <p>Lorem ipsum dolor sit amet c commodi eaque dolorem ipsa laudantium.</p>
        </div>
        <div class="section__bottom">
            <div class="card-section-3">
                <h2>Standard</h2>
                <div class="blue-number">

                </div>
                <p>15 Projects</p>
                <p>30GB Storage</p>
                <p>Unlimited Users</p>
                <button class="btn">START TODAY</button>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'SectionFour'
}
</script>

<style lang='scss' scoped>

@import '../assets/style/mixins.scss';

    .section {
        min-height: 600px;
        display: flex;
        flex-direction: column;
        align-items: center;
        text-align: center;

        background-image: url(../assets/img/background1.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        background-position: center;

        &__top {
            max-width: var(--container-xx-small);
            display: flex;
            flex-direction: column;

            h2 {
                color: white;
                margin: 70px 0px 20px 0px;
            }

            p {
                color: white;
            }
        }

        &__bottom {
            display: flex;
            justify-content: center;

            .card-section-3 {
                background: white;
                height: 300px;
                width: 200px;
                margin-top: 50px;

                display: flex;
                flex-direction: column;
                padding: 20px;

                .blue-number {

                }

                .btn {
                    @include button-white;
                }

                .btn:hover {
                    @include button-orange-bis;
                }
            }
        }
    }
</style>