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
                <button>ciao</button>
            </div>
        </div>
        <div class="header__bottom">
            
        </div>

    </header>
</template>

<script>
export default {
    name: 'BaseHeader'
}
</script>

<style lang='scss'>

.header {

    height: 300px;
    background-image: url(../assets/img/1-hero-image.png);
    background-repeat: no-repeat;
    width: 100%;

    &__top {
        margin: auto;
        max-width: var(--container-medium);
        display: flex;
        height: 50px;
        justify-content: space-between;
        align-items: center;
        

        .header-logo {
            height: 100%;
        }
    }

    &__bottom {
        height: 300px;
        display: flex;
        background-image: url(../assets/img/1-hero-image.png);
        background-repeat: no-repeat;

        width: 100%;
    }

    &__nav {
        display: flex;

        a {
            text-decoration: none;
        }
    }
}

</style>