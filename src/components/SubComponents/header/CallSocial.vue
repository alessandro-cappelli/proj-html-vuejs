<template>
    <section>
        <div class="ms_container_info">
            <div class="container">
                <div class="row">
                    <div class="col d-flex">
                        <div class="col d-flex">
                            <div class="ms_icon_call"><i class="fas fa-phone-alt"></i></div>
                            <p>Call us for a Free Quote: 1.800.555.6789</p>
                        </div>

                    <div class="col d-flex justify-content-end ms_container_social">
                        <ul>
                            <li><a href="#"><i class="fab fa-facebook-f"></i></a></li>
                            <li><a href="#"><i class="fab fa-twitter"></i></a></li>
                            <li><a href="#"><i class="fab fa-instagram"></i></a></li>
                            <li><a href="#"><i class="fab fa-youtube"></i></a></li>
                        </ul>
                    </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'CallSocial',
}
</script>

<style lang='scss' scoped>
.row{
    height: 50px;
    align-items: center;
}
.ms_container_info{
    background-color: #6abf17;
    height: 50px;
    color: white;
}

ul li{
    display: inline-block;
    text-decoration: none;
    margin-left: 15px;
}

ul li a{
    color: white;
}

.ms_icon_call{
    margin-right: 15px;
}

</style>