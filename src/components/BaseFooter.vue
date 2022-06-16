<template>
    <footer class="footer">
        <div class="footer__logo">
            <img src="../assets/img/logo_seo_1x.png" alt="">
        </div>
        <div class="footer__link">
            <a class="footer-link" href="#">Home</a>
            <a class="footer-link" href="#">Who We Are</a>
            <a class="footer-link" href="#">What We Do</a>
            <a class="footer-link" href="#">Where We Work</a>
            <a class="footer-link" href="#">Careers</a>
            <a class="footer-link" href="#">News </a>
        </div>
        <div class="footer__copyright">
            <p> © Copyright 2012 - 2020 | 
                Avada Theme by <a href="#"><strong>ThemeFusion</strong></a> | 
                All Rights Reserved | 
                Powered by <a href="#"><strong>WordPress</strong></a>
            </p>
        </div>
        <div class="footer__social">
            <p>
                <i class="fa-brands fa-facebook-f footer__icon"></i>
                <i class="fa-brands fa-instagram footer__icon"></i>
                <i class="fa-brands fa-twitter footer__icon"></i>
                <i class="fa-brands fa-youtube footer__icon"></i>

            </p>
        </div>
        
    </footer>
</template>

<script>
export default {
    name:'BaseFooter',
}
</script>

<style lang='scss' scoped>

.footer {
    display: flex;
    flex-direction: column;
    align-items: center;
    height: 280px;
    background: white;

    &__logo {
        margin: 80px 0px;
        cursor: pointer;
        
        img {
            width: 230px
        }

    }

    &__link {
        display: flex;
        align-items: center;
        margin-bottom: 80px;

        a {
            text-decoration: none;
            color: var(--grey);
            margin: 0px 20px;
            font-weight: 500;
            font-size: 19px;

        }

        a:hover {
            color: #ffa837;
        }
    }

    &__copyright {

        a {
           text-decoration: none;
           color: var(--grey) 
        }

        p {
            margin-bottom: 50px
        }
    }

    &__icon {
        font-size: 30px;
        color: var(--grey);
        margin: 0px 0px 60px 25px;
        cursor: pointer;

    }

    &__icon:hover {
        color: var(--orange)
    }

    

};

</style>