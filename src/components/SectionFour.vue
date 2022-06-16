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
                    <div class="dollaro">$</div>
                    <div class="numero-grande">19</div>
                    <div class="col-dx">
                        <div class="novantanove">99</div>
                        <div class="monthly">monthly</div>
                    </div>
                </div>
                <p>15 Projects</p>
                <p class="gigabyte">30GB Storage</p>
                <p>Unlimited Users</p>
                <button class="btn">START TODAY</button>
            </div>
            <div class="card-section-3">
                <h2>Standard</h2>
                <div class="blue-number">
                    <div class="dollaro">$</div>
                    <div class="numero-grande">19</div>
                    <div class="col-dx">
                        <div class="novantanove">99</div>
                        <div class="monthly">monthly</div>
                    </div>
                </div>
                <p>15 Projects</p>
                <p class="gigabyte">30GB Storage</p>
                <p>Unlimited Users</p>
                <button class="btn">START TODAY</button>
            </div>
            <div class="card-section-3">
                <h2>Standard</h2>
                <div class="blue-number">
                    <div class="dollaro">$</div>
                    <div class="numero-grande">19</div>
                    <div class="col-dx">
                        <div class="novantanove">99</div>
                        <div class="monthly">monthly</div>
                    </div>
                </div>
                <p>15 Projects</p>
                <p class="gigabyte">30GB Storage</p>
                <p>Unlimited Users</p>
                <button class="btn">START TODAY</button>
            </div>
            <div class="card-section-3">
                <h2>Standard</h2>
                <div class="blue-number">
                    <div class="dollaro">$</div>
                    <div class="numero-grande">19</div>
                    <div class="col-dx">
                        <div class="novantanove">99</div>
                        <div class="monthly">monthly</div>
                    </div>
                </div>
                <p>15 Projects</p>
                <p class="gigabyte">30GB Storage</p>
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

                display: flex;
                flex-direction: column;
                align-items: center;
                justify-content: center;
                padding: 20px;
                margin: 60px 10px;

                .gigabyte {
                    margin: 20px 0px;
                }

                .blue-number {
                    display: flex;
                    margin: 20px 0px;

                    .dollaro {
                        font-size: 11px;
                        font-weight: 800;
                        margin-top: 3px;
                    }

                    .numero-grande {
                        font-size: 25px;
                        font-weight: 800;
                        color: var(--blue)
                    }

                    .col-dx {
                        display: flex;
                        flex-direction: column;
                        align-items: flex-start;

                        .novantanove {
                            font-size: 9px;
                            margin-top: 3px;
                            font-weight: 800;
                            color: var(--blue)
                        }

                        .monthly {
                            font-size: 7px;
                            color: var(--grey);
                            margin-top: 2px;
                            font-style: italic
                        }
                    }

                }

                .btn {
                    @include button-white;
                    margin-top: 20px;
                }

                .btn:hover {
                    @include button-orange-bis;
                }

                p {
                    color: var(--grey);
                    font-size: 12px;
                }
            }
        }
    }
</style>