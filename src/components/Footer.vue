<template>
    <section>
        <FirstFooter/>

        <SecondFooter/>
    </section>
</template>

<script>
import FirstFooter from './SubComponents/footer/FirstFooter.vue'
import SecondFooter from './SubComponents/footer/SecondFooter.vue'


export default {
    name: 'Footer',

    components:{
        FirstFooter,
        SecondFooter
    }
}
</script>

<style lang="scss" scoped>

</style>