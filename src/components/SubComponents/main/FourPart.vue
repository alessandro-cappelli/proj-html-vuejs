<template>
    <section class="ms_container_fourpart">
        <div class="container">
            <div class="row">
                <div class="col ms_title">
                    <p>HAPPY CUSTOMERS</p>
                    <h1>Testimonials</h1>
                </div>
            </div>
        </div>

        <div class="container ms_container_col">
            <div class="row justify-content-between ms_row_col">
                <div class="col-3">
                    <img src="../../../assets/img/avada-movers-serviceonephoto-final.jpg">
                    <div>
                        <h3>Two Man Teams</h3>
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Aliquam numquam deleniti sit, nulla quibusdam non voluptates pariatur repudiandae ad nam </p>
                        <div class="bottom">
                            <span><a href="#">read more</a></span>
                        </div>
                    </div>
                </div>
                <div class="col-3">
                    <img src="../../../assets/img/avada-movers-servicetwophoto-final.jpg">
                    <div>
                        <h3>Two Man Teams</h3>
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Aliquam numquam deleniti sit, nulla quibusdam non voluptates pariatur repudiandae ad nam </p>
                        <div class="bottom">
                            <span><a href="#">read more</a></span>
                        </div>
                    </div>
                </div>
                <div class="col-3">
                    <img src="../../../assets/img/avada-movers-servicethreephoto-final.jpg">
                    <div>
                        <h3>Two Man Teams</h3>
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Aliquam numquam deleniti sit, nulla quibusdam non voluptates pariatur repudiandae ad nam </p>
                        <div class="bottom">
                            <span><a href="#">read more</a></span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>


<script>
export default {
    name: 'fourpart',
}
</script>


<style lang='scss' scoped>
.ms_container_fourpart{
    background-image: url('../../../assets/img/avada-movers-testimonial-background.jpg');
    background-size: cover;
}
.container{
    text-align: center;
}

.ms_title{
    margin-top: 100px;

    p{
        color: #93989b;
        font-weight: bold;
    }

    h1{
        color: #6bbb14;
        font-size: 40px;
    }
}

img{
    width: 100%;
}

.col-3{
    background-color: #e9e9e9;
    padding-top: 12px;
    padding-bottom: 12px;

    div{
        background-color: white;
        margin-top: 10px;
        padding-bottom: 16px;

        h3{
            color: #1975c0;
            padding-top: 25px;
        }

        p{
            line-height: 30px;
            margin-top: 14px;
            margin-bottom: 30px;
        }

        a{
            color: white;
            text-decoration: none;
            text-transform: uppercase;
            font-weight: bold;
            background-color: #1975c0;
            padding-top: 8px;
            padding-bottom: 8px;
            padding-left: 20px;
            padding-right: 20px;
            border-radius: 20px;
        }
    }
}

.ms_container_col{
    margin-top: 45px;
}

.ms_row_col{
    margin-bottom: 100px;
}

</style>