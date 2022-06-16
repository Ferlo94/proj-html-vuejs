<template>
    <main class="main">
        <SectionOne/>
        <SectionTwo/>
        <SectionThree/>
    </main>
</template>

<script>

import SectionOne from './SectionOne.vue'
import SectionTwo from './SectionTwo.vue'
import SectionThree from './SectionThree.vue'

export default {
    name: 'BaseMain',

    components: {
        SectionOne,
        SectionTwo,
        SectionThree,
    }
}
</script>



<style lang='scss'>

</style>