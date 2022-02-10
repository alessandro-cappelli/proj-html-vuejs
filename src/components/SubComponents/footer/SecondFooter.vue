<template>
    <section class="ms_container_secondfooter">
        <div class="container">
            <div class="row">
                <div class="col">
                    <p>&copy; Copyright 2012-2020  |  Avada Theme by ThemeFusion  |  All Rights Reserved  |  Powered by WordPress</p>

                    <div>
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
        
    </section>
</template>


<script>
export default {
    name: 'SecondFooter',
}
</script>


<style lang='scss' scoped>
.ms_container_secondfooter{
    background-color: #6abf17;
    color: white;
}
.col{

    p{
        margin-top: 35px;
    }

    li{
        display: inline-block;
        margin-top: 22px;
        margin-left: 20px;
        margin-bottom: 35px;
    }

    a{
        text-decoration: none;
        color: white;
    }
}

.row{
    text-align: center;
}

</style>