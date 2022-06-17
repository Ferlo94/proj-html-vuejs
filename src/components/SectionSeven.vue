<template>
    <section class="section">
        <div class="section__container">
            <h2>Start Your Free Consultation</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsam praesentium ips adipisci necessit porro corrupti</p>
            <button class="btn">CONTACT US NOW</button>
        </div>
    </section>
</template>

<script>
export default {
    name: 'SectionSeven'
}
</script>

<style lang= 'scss' scoped>

@import '../assets/style/mixins.scss';

.section {
    min-height: 550px;
    display: flex;

    background-image: linear-gradient(to bottom, rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url("../assets/img/CTA-seo-1.jpg");
    
    justify-content: center;
    align-items: center;

    &__container {

        max-width: var(--container-x-small);
        display: flex;
        flex-direction: column;
        text-align: center;
        align-items: center;


        h2 {
            color: white;
            font-size: 30px;
        }

        p {
            color: white;
            margin: 30px 0px;
        }

        .btn {
            @include button-orange-bis;
            max-width: 300px;
        }

    }

    
    
}

</style>