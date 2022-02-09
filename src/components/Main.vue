<template>
    <section>
        <FirstPart />

        <SecondPart />
    </section>
</template>

<script>
import FirstPart from './SubComponents/main/FirstPart.vue'
import SecondPart from './SubComponents/main/SecondPart.vue'

export default {
    name: 'Main',

    components:{
        FirstPart,
        SecondPart,
    }
}
</script>

<style lang='scss' scoped>

</style>