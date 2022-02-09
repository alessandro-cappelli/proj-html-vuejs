<template>
    <section>
        <FirstPart />

        <SecondPart />

        <ThreePart />
    </section>
</template>

<script>
import FirstPart from './SubComponents/main/FirstPart.vue'
import SecondPart from './SubComponents/main/SecondPart.vue'
import ThreePart from './SubComponents/main/ThreePart.vue'


export default {
    name: 'Main',

    components:{
        FirstPart,
        SecondPart,
        ThreePart,
    }
}
</script>

<style lang='scss' scoped>

</style>