<template>
  <div class="ms_container_slogan">
    <div class="container">
      <div class="row">
        <div class="col">
          <p class="mb-2">moving without the hassle</p>
          <h1 class="mb-2">we make it simple</h1>
          <p>professional service with quality and customer satisfaction</p>
        </div>
      </div>
    </div>    
  </div>
</template>


<script>
export default {
    name: 'Slogan'
}
</script>


<style lang="scss" scoped>
.row{
  text-align: center;
  text-transform: uppercase;
  font-weight: bold;
}

h1{
  font-size: 65px;
}

p{
  color: #777777;
  font-size: 16px;
}

.ms_container_slogan{
  background-image: url("../../../assets/img/avada-movers-homeherobackground-final.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  height:750px;
}

.col{
  margin-top: 312px;
}
</style>