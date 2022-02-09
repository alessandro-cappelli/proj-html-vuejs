<template>
    <section class="ms_container_firstfooter">
        <div class="container ms_container_col">
            <div class="row justify-content-between ms_row_col">
                <div class="col-4">
                    <h3>about</h3>
                    <div>
                        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Excepturi tempora distinctio exercitationem itaque at. Deleniti dolorum quas, facere minus at dolor eveniet. Sunt eos rerum.</p>
                    </div>
                    <div class="ms_container_img">
                        <img src="../../../assets/img/avada-movers-logo.png" >
                    </div>
                </div>
                <div class="col-4">
                    <h3>avada movers</h3>
                    <div>
                        <ul>
                            <li><a href="#">&rsaquo; Home</a></li>
                            <li><a href="#">&rsaquo; Rates</a></li>
                            <li><a href="#">&rsaquo; Testimonials</a></li>
                            <li><a href="#">&rsaquo; Blog</a></li>
                            <li><a href="#">&rsaquo; Free Quote</a></li>
                        </ul>
                    </div>
                </div>
                <div class="col-4">
                    <h3>recent posts</h3>
                    <div>
                        <ul>
                            <li><a href="#">&rsaquo; Heading Out To College?</a></li>
                            <li><a href="#">&rsaquo; Moving Your Business?</a></li>
                            <li><a href="#">&rsaquo; Outstanding Quality</a></li>
                            <li><a href="#">&rsaquo; Cost of Moving</a></li>
                            <li><a href="#">&rsaquo; Best Moving Tips</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>


<script>
export default {
    name: 'FirstFooter',
}
</script>


<style lang='scss' scoped>
.col-4{

    h3{
       text-transform: uppercase; 
       margin-bottom: 20px;
    }

    p{
        line-height: 30px;
    }

    li{
        list-style: none;
        line-height: 50px;
    }

    a{
        text-decoration: none;
        color: black;
    }

    a:hover{
        color: #6bbb14;
    }
}

.ms_container_img{
    margin-top: 40px;
}



.ms_container_col{
    margin-top: 70px;
}

.ms_row_col{
    margin-bottom: 70px;
}


</style>