<template>
    <section class="section">
        <div class="section__top">
            <h2>What Our Clients Say</h2>
        </div>
        <div class="section__img">
            <img src="../assets/img/testimonials-2.jpg" alt="">
        </div>
        <div class="section__mid">
            <p class="p-top">Lorem ipsum dolor sit amet consectetur adipisicing elit. modi autem ducesciunt itaque accusamus, dolorum culpa quod Possimus provident iusto officia optio.</p>
            <p class="p-mid"><strong>Luis Desalvo</strong>, CREO TECH</p>
            <div class="p-bottom">
                <i class="fa-solid fa-circle icon"></i>
                <i class="fa-regular fa-circle icon"></i>
            </div>
        </div>
            <hr>
        <div class="section__bottom">
            <img src="../assets/img/clients_partner_5-200x202.png" alt="">
            <img src="../assets/img/clients_partner_6-200x202.png" alt="">
            <img src="../assets/img/clients_partner_1-200x202.png" alt="">
            <img src="../assets/img/clients_partner_2-200x202.png" alt="">
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style lang='scss' scoped>
    .section {
        min-height: 600px;
        background: #ffff;
        text-align: center;
        display: flex;
        flex-direction: column;
        align-items: center;

        &__top {
            h2 {
                font-size: 30px;
                margin: 80px 0px 40px 0px;
            }
        }

        &__img {
            img {
                border-radius: 50%;
            }
        }

        &__mid {
            max-width: var(--container-small);
            text-align: center;
            font-weight: 500;
            color: var(--grey);

            .p-top {
                margin: 30px 0px 30px;
                font-style: italic;
            }

            .p-mid {
                color: black;
            }

            .p-bottom {
                color: black;

                .icon {
                    margin: 40px 5px 90px 5px;
                }

            }
            
        }

        hr {
            width: var(--container-medium);

        }

        &__bottom {
            display: flex;
            justify-content: center;
            max-width: var(--container-medium);

            img {
                margin: 80px 80px;
            }
        }
    }
</style>