<template>
    <div class="ms_container_nav">
        <div class="container">
            <div class="row">
                <div class="col-2">
                    <img src="../../../assets/img/avada-movers-logo.png">
                </div>

                <div class="col d-flex justify-content-end ms_container_nav">
                    <ul>
                        <li><a href="#">Home</a></li>
                        <li><a href="#">Rates</a></li>
                        <li><a href="#">Testimonials</a></li>
                        <li><a href="#">FAQ</a></li>
                        <li><a href="#">Blog</a></li>
                        <li><a href="#">Contact</a></li>
                    </ul>

                    <span><a class="button" href="#">free quote</a></span>
                    </div>
                </div>
            </div>
        </div>
</template>


<script>
export default {
    name: 'Navbar',


}
</script>


<style lang="scss" scoped>
.row{
    height: 75px;
    align-items: center;
}

ul li{
    display: inline-block;
    margin-left: 45px;

    a{
        text-decoration: none;
        color: black;
        font-weight: bold;
    }

    a:hover{
        color: #6abf17;
    }
}

span{
    margin-left: 40px;
}

.button{
    color: white;
    text-decoration: none;
    text-transform: uppercase;
    background-color: #1975c0;
    padding-top: 8px;
    padding-bottom: 8px;
    padding-left: 20px;
    padding-right: 20px;
    border-radius: 20px;
}

img{
    width: 100%;
}

.ms_container_nav{
    margin-top: 15px;
}
</style>