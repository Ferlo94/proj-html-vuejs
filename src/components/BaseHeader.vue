<template>
    <header class="header">
        <div class="header__top">
            <div class="header-logo">
                <img src="../assets/img/logo_seo_w_1x.png" alt="">
            </div>
            <div class="header__nav">
                <a class="header-link" href="#">Home</a>
                <a class="header-link" href="#">Who We Are</a>
                <a class="header-link" href="#">What We Do</a>
                <a class="header-link" href="#">Where We Work</a>
                <a class="header-link" href="#">Careers</a>
                <a class="header-link" href="#">News</a>
                <button>GET IN TOUCH NOW</button>
            </div>
        </div>
        <div class="header__bottom-container">
            <div class="header__bottom">
                <h1>SEM Campaigns Made <br> Simple With Avada</h1>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Sunt culpa provident maxime.</p>
                <button class="btn-header-orange">BUY AVADA NOW</button>
                <button class="btn-header-blue">CONTACT US</button>
            </div>
        </div>
    </header>
</template>

<script>
export default {
    name: 'BaseHeader'
}
</script>

<style lang='scss'>

@import '../assets/style/mixins.scss';

.header {

    height: 700px;
    background-image: url(../assets/img/1-hero-image.png);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;

    &__top {
        @include container-medium;
        display: flex;
        height: 60px;
        justify-content: space-between;
        align-items: center;
        

        .header-logo {
            height: 100%;

            img {
                padding: 10px;
                cursor: pointer;
            }
        }
    }

    &__bottom-container {
        @include container-medium;
        display: flex;
        flex-direction: column;
        justify-content: center;
        height: 80%;
        
        .header__bottom {

             max-width: 480px;
            h1 {
                color: var(--white);
                font-size: 40px;
                margin-bottom: 23px;
            };
            p {
                color: var(--white);
                margin-bottom: 23px;
            };
           

            .btn-header-orange {
                @include button-orange;
                margin-right: 20px;
            }

            .btn-header-blue {
                @include button-blue;
            }
        }
    }


    &__nav {
        display: flex;
        align-items: center;

        a {
            text-decoration: none;
            color: var(--white);
            margin: 0px 20px;

        }

        a:hover {
            color: #ffa837;
        }

        button {
            @include button-orange;
        }

    }
}

</style>