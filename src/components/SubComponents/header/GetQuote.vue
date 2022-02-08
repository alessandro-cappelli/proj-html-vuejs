<template>
    <div class="ms_container_link">
        <div class="container">
            <div class="row">
                <div class="col d-flex">
                    <span><a href="#"><i class="far fa-paper-plane"></i> get a free quote online now!</a></span>
                </div>
            </div>
        </div>   
    </div>
</template>


<script>
export default {
    name: 'GetQuote'
}
</script>


<style lang='scss' scoped>
.ms_container_link{
    height: 100px;
    background-color: #1775bf;
}

a{
    text-transform: uppercase;
    text-decoration: none;
    color: white;

    &:hover{
        text-decoration: underline;
    }
}

.col{
    height: 100px;
    align-items: center;
    justify-content: center;
    color: white;
}

</style>