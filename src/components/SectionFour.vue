<template>
    <section class="section">
        <div class="section__top">
            <h2>Our Plans</h2>
            <p>Lorem ipsum dolor sit amet c commodi eaque dolorem ipsa laudantium.</p>
        </div>
        <!-- 1 -->
        <div class="section__bottom">
            <div class="card-section-4">
                <h2>Standard</h2>
                <div class="blue-number">
                    <div class="dollaro">$</div>
                    <div class="numero-grande">19</div>
                    <div class="col-dx">
                        <div class="novantanove">99</div>
                        <div class="monthly">monthly</div>
                    </div>
                </div>
                <p>5 Projects</p>
                <p class="gigabyte">5 GB Storage</p>
                <p>Unlimited Users</p>
                <button class="btn">START TODAY</button>
            </div>
            <!-- 2 -->
            <div class="card-section-4">
                <h2>Standard</h2>
                <div class="blue-number">
                    <div class="dollaro">$</div>
                    <div class="numero-grande">29</div>
                    <div class="col-dx">
                        <div class="novantanove">99</div>
                        <div class="monthly">monthly</div>
                    </div>
                </div>
                <p>10 Projects</p>
                <p class="gigabyte">15 GB Storage</p>
                <p>Unlimited Users</p>
                <button class="btn">START TODAY</button>
            </div>
            <!-- 3 -->
            <div class="card-section-4">
                <h2>Standard</h2>
                <div class="blue-number">
                    <div class="dollaro">$</div>
                    <div class="numero-grande">39</div>
                    <div class="col-dx">
                        <div class="novantanove">99</div>
                        <div class="monthly">monthly</div>
                    </div>
                </div>
                <p>15 Projects</p>
                <p class="gigabyte">30 GB Storage</p>
                <p>Unlimited Users</p>
                <button class="btn">START TODAY</button>
            </div>
            <!-- 4 -->
            <div class="card-section-4">
                <h2>Standard</h2>
                <div class="blue-number">
                    <div class="dollaro">$</div>
                    <div class="numero-grande">59</div>
                    <div class="col-dx">
                        <div class="novantanove">99</div>
                        <div class="monthly">monthly</div>
                    </div>
                </div>
                <p>Unlimited Projects</p>
                <p class="gigabyte">Unlimited Storage</p>
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
                font-size: 30px;
            }

            p {
                color: white;
            }
        }

        &__bottom {
            display: flex;
            justify-content: center;
            width: var(--container-medium);

            .card-section-4 {
                
                background: white;
                height: 350px;
                width: calc(100% / 4);

                display: flex;
                flex-direction: column;
                align-items: center;
                justify-content: center;
                padding: 20px;
                margin: 60px 10px 80px 10px;
                cursor: pointer;
                border: solid 4px transparent;

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
                    font-weight: 500;
                }
            }

            .card-section-4:hover {
                border: 4px solid var(--orange);
            }
        }
    }
</style>