
<script>
export default {
  name: 'sponsor',
}
</script>
<template>
  <div>
    <div class="back">
      <div class="container">
        <div class="row">
          <div class="col-2 box">
            <img src="../../assets/client2.png" alt="">
          </div>
          <div class="col-2 box">
            <img src="../../assets/client3.png" alt="">
          </div>
          <div class="col-2 box">
            <img src="../../assets/client4.png" alt="">
          </div>
          <div class="col-2 box">
            <img src="../../assets/client7.png" alt="">
          </div>
          <div class="col-2 box">
            <img src="../../assets/client9.png" alt="">
          </div>
          <div class="col-2 box">
            <img src="../../assets/client10.png" alt="">
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.container{
  margin-top: 50px;
  margin-bottom: 30px;
}
  .back{
    background-color: black;
    padding: 18px;
  }
  .box{
    border: 1px solid white;
    border-radius: 30px;
  }
  img{
    width: 100%;
  }
</style>