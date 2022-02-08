<template>
    <section>
        <CallSocial />

        <Navbar />
        
        <Slogan />

        <GetQuote/>
    </section>
</template>

<script>
import CallSocial from './SubComponents/header/CallSocial.vue'
import Navbar from './SubComponents/header/Navbar.vue'
import Slogan from './SubComponents/header/Slogan.vue'
import GetQuote from './SubComponents/header/GetQuote.vue'

export default {
    name: 'Header',

    components:{
        CallSocial,
        Navbar,
        Slogan,
        GetQuote,
    }
}
</script>

<style lang='scss' scoped>

</style>