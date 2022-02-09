<template>
    <div class="ms_container_firstpart">
        <div class="container-fluid">
            <div class="row">
                <div class="col">
                    <p class="ms_free">HEADACHE FREE</p>
                    <h1 class="mt-2">Award Winning</h1>
                    <h1 class="mb-4">Moving Company</h1>
                    <p class="ms_lorem mb-5">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Omnis dignissimos veniam recusandae iure odio, architecto fugit facere repellat consequuntur repellendus id voluptate ducimus nulla quos optio perferendis quas doloribus sit!</p>
                    <span><a href="#">read our testimonials</a></span>
                </div>
            </div>
        </div>     
    </div>
</template>


<script>
export default {
    name: 'FirstPart'
}
</script>


<style lang='scss' scoped>
.ms_container_firstpart{
    background-color: #e9e9e9;
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
    font-weight: bold;
    background-color: #1975c0;
    padding-top: 8px;
    padding-bottom: 8px;
    padding-left: 20px;
    padding-right: 20px;
    border-radius: 20px;
}

</style>