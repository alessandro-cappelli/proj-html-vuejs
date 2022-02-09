<template>
    <section class="ms_container_threepart">
        <div class="container">
            <div class="row">
                <div class="col-5">
                    <div class="ms_container">
                        <div class="ms_part_start">
                            <p>WE REMOVE THE HEADACHE FROM MOVING</p>
                            <h1>Move With Ease</h1>
                        </div>

                        <div class="ms_part_center">
                            <p>
                                With our super simple service we can take you from getting a quote, right through to being in your new home with 
                                all of your belongings securely packed and safely delivered, even in the rooms of your 
                                choice.
                            </p>
                        </div>

                        <div class="ms_part_end">
                            <span><a href="#">get a free quote now</a></span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>


<script>
export default {
    name: 'ThreePart',
}
</script>


<style lang='scss' scoped>
.ms_container_threepart{
    background-image: url('../../../assets/img/avada-movers-movewithease-background-new.jpg');
    background-size: cover;
    height: 900px;
    
}

.row{
    text-align: center;
    justify-content: end;

    .col-5{
        background-color: #5aa511;
        color: white;
        padding-top: 10px;
        padding-bottom: 10px;
    }

    .ms_container{
        background-color: #6abf17;
    }
}

.ms_part_start{
    font-weight: bold;

    p{
        padding-top: 35px;
        margin-bottom: 9px;
    }
    h1{
        font-size: 48px;
    }
}

.ms_part_center{
    line-height: 30px;
    margin-bottom: 35px;
}

.ms_part_end{
    padding-bottom: 41px;
    a{
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
}
</style>