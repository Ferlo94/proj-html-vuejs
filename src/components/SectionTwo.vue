<template>
    <section class="section">
        <div class="section__top">
            <h2>See Our Top Notch Services</h2>
            <p>Lorem, ipsum dolor sit amet consectet Inventore corrupti eveniet, accusantium.</p>
        </div>
        <div class="section__bottom">
            <div class="card-section-2">
                <i class="fa-brands fa-google icon"></i>
                <h3>Establish Goals</h3>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Molesti t consectetur, adipis. Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum nihil debitis quas illo hic. </p>
                <p class="orange-p">Read More &nbsp; <i class="fa-solid fa-angle-right"></i></p>
            </div>
            <div class="card-section-2">
                <i class="fa-solid fa-gear icon"></i>
                <h3>Establish Goals</h3>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Molesti t consectetur, adipis. Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum nihil debitis quas illo hic. </p>
                <p class="orange-p">Read More &nbsp; <i class="fa-solid fa-angle-right"></i></p>
            </div>
            <div class="card-section-2">
                <i class="fa-solid fa-building icon"></i>
                <h3>Establish Goals</h3>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Molesti t consectetur, adipis. Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum nihil debitis quas illo hic. </p>
                <p class="orange-p">Read More &nbsp; <i class="fa-solid fa-angle-right"></i></p>
            </div>
            <div class="card-section-2">
                <i class="fa-solid fa-chart-column icon"></i>
                <h3>Establish Goals</h3>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Molesti t consectetur, adipis. Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsum nihil debitis quas illo hic. </p>
                <p class="orange-p">Read More &nbsp; <i class="fa-solid fa-angle-right"></i></p>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'SectionTwo'
}
</script>

<style lang= 'scss' scoped>

    .section {
        
        min-height: 650px;
        display: flex;
        flex-direction: column;
        align-items: center;
        text-align: center;

        background-image: url(../assets/img/pattern_background.png);
        background-color: #051642;
        background-repeat: no-repeat;
        background-size: cover;
        background-position: center;
        
        &__top {
            
            max-width: var(--container-xx-small);
        

            display: flex;
            flex-direction: column;
            align-items: center;

            h2 {
                color: white;
                margin-top: 70px;
                
            }

            p {
                color: white;
                margin: 20px 0px ;
            }
        }

        &__bottom {
            display: flex;
            max-width: var(--container-medium);
            justify-content: center;

            .card-section-2 {
                background: #071b50;
                height: 280px;
                width: 210px;

                display: flex;
                flex-direction: column;
                justify-content: center;
                align-items: center;
                text-align: center;
                padding: 20px;
                margin: 10px;

                .icon {
                    color: var(--orange);
                    font-size: 20px;
                    

                }

                h3 {
                    margin: 20px 0px 15px 0px;
                    font-size: 16px;
                    color: white;
                }

                p {
                    font-size: 12px;
                    font-weight: 500;
                    color: white;
                }

                .orange-p {
                    color: var(--orange);
                    margin-top: 20px;

                    .fa-angle-right {
                        font-size: 10px;
                    }
                }
            }
        }
    }

</style>