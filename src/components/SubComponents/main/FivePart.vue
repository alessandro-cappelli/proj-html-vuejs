<template>
    <div class="ms_container_firstpart">
        <div class="container-fluid">
            <div class="row">
                <div class="col">
                    <h1 class="mb-4">Request A Free Quote</h1>
                    <p class="ms_lorem mb-5">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Omnis dignissimos veniam recusandae iure odio, architecto fugit facere repellat consequuntur repellendus id </p>
                    <span><a href="#">click here</a></span>
                </div>
            </div>
        </div>
        <div class="ms_line_green"></div>     
    </div>
</template>


<script>
export default {
    name: 'FirstPart'
}
</script>


<style lang='scss' scoped>
.ms_container_firstpart{
    background-image: url('../../../assets/img/avada-movers-request-quote-background.jpg');
    background-size: cover;
}

.col{
    margin-top: 100px;
    margin-bottom: 100px;
}

.container-fluid{
    text-align: center;
    width: 763px;
    margin: 0 auto;
}

h1{
    font-size: 40px;
    color: #6bbb14;
}

.ms_free{
    font-weight: bold;
    color: #93989b;
}

.ms_lorem{
    line-height: 30px;
}

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

.ms_line_green{
    height: 15px;
    background-color: #6bbb14;
}
</style>