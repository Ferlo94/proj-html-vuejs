<template>
    <header class="header">
        <div class="header__top">
            <div class="header-logo">
                <img src="../assets/img/logo_seo_w_1x.png" alt="">
            </div>
            <div class="header__nav">
                <a href="#">Link</a>
                <a href="#">Link</a>
                <a href="#">Link</a>
                <a href="#">Link</a>
                <a href="#">Link</a>
                <a href="#">Link</a>
                <button>GET IN TOUCH NOW</button>
            </div>
        </div>
        <div class="header__bottom">
            <h1>SEM Campaign</h1>
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

    height: 900px;
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

    &__bottom {
        @include container-medium;
        display: flex;
        flex-direction: column;
    }

    &__nav {
        display: flex;
        align-items: center;

        a {
            text-decoration: none;
            color: var(--white);
            margin: 0px 20px;

        }

        button {
            @include button-orange;
        }

    }
}

</style>