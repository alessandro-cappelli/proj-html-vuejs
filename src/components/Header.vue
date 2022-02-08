<template>
    <section>
        <CallSocial />

        <Navbar />
        
    </section>
</template>

<script>
import CallSocial from './SubComponents/header/CallSocial.vue'
import Navbar from './SubComponents/header/Navbar.vue'



export default {
    name: 'Header',

    components:{
        CallSocial,
        Navbar,
    }
}
</script>

<style lang='scss' scoped>

</style>