<template>
    <section>
        <FirstPart />

        <SecondPart />

        <ThreePart />

        <FourPart/>

        <FivePart/>
    </section>
</template>

<script>
import FirstPart from './SubComponents/main/FirstPart.vue'
import SecondPart from './SubComponents/main/SecondPart.vue'
import ThreePart from './SubComponents/main/ThreePart.vue'
import FourPart from './SubComponents/main/FourPart.vue'
import FivePart from './SubComponents/main/FivePart.vue'




export default {
    name: 'Main',

    components:{
        FirstPart,
        SecondPart,
        ThreePart,
        FourPart,
        FivePart,
    }
}
</script>

<style lang='scss' scoped>

</style>