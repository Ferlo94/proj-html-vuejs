<template>
    <main class="main">
        <SectionOne/>
        <SectionTwo/>
        <SectionThree/>
        <SectionFour/>
        <SectionFive/>
    </main>
</template>

<script>

import SectionOne from './SectionOne.vue'
import SectionTwo from './SectionTwo.vue'
import SectionThree from './SectionThree.vue'
import SectionFour from './SectionFour.vue'
import SectionFive from './SectionFive.vue'

export default {
    name: 'BaseMain',

    components: {
        SectionOne,
        SectionTwo,
        SectionThree,
        SectionFour,
        SectionFive,
    }
}
</script>



<style lang='scss'>

</style>