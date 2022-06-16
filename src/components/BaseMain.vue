<template>
    <main class="main">
        <SectionOne/>
        <SectionTwo/>
    </main>
</template>

<script>

import SectionOne from './SectionOne.vue'
import SectionTwo from './SectionTwo.vue'

export default {
    name: 'BaseMain',

    components: {
        SectionOne,
        SectionTwo,
    }
}
</script>



<style lang='scss'>

</style>