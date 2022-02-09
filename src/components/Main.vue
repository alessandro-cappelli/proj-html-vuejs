<template>
    <section>
        <FirstPart />

        <SecondPart />

        <ThreePart />

        <FourPart/>
    </section>
</template>

<script>
import FirstPart from './SubComponents/main/FirstPart.vue'
import SecondPart from './SubComponents/main/SecondPart.vue'
import ThreePart from './SubComponents/main/ThreePart.vue'
import FourPart from './SubComponents/main/FourPart.vue'



export default {
    name: 'Main',

    components:{
        FirstPart,
        SecondPart,
        ThreePart,
        FourPart,
    }
}
</script>

<style lang='scss' scoped>

</style>