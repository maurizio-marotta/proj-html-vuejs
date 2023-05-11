
<script>
export default {
  name: 'article',
}
</script>
<template>
  <div class="back">
    <div class="title">
      <h2 class="text-center color-white">Upcoming Matchs</h2>
    </div>
    <div class="play">
      <div class="container-top">
        <div class="row justify-content-md-center">
          <span class="col-md-auto"><img src="../../assets/club-2.png" alt="club"><strong>United Fs Club</strong> </span>
          <h2 class="col-md-auto" >vs</h2>
          <span class="col-md-auto"><strong>Istanbul Sports </strong> <img src="../../assets/club-1.png" alt="club"></span>
        </div>
      </div>
      <div class="container-bottom">
        <span><strong>
          <i class="fa-sharp fa-regular fa-calendar-days"></i> May 21, 2022 18:05 pm
          <i class="fa-solid fa-circle-plus"></i> Expert Stadium </strong>
        </span>
      </div>
    </div>
    <div class="play">
      <div class="container-top">
        <div class="row justify-content-md-center">
          <span class="col-md-auto"><img src="../../assets/club-3.png" alt="club"><strong>Inter Club</strong> </span>
          <h2 class="col-md-auto" >vs</h2>
          <span class="col-md-auto"><strong>MIlan FC</strong> <img src="../../assets/club-4.png" alt="club"></span>
        </div>
      </div>
      <div class="container-bottom">
        <span><strong>
          <i class="fa-sharp fa-regular fa-calendar-days"></i> May 21, 2022 18:05 pm
          <i class="fa-solid fa-circle-plus"></i> Expert Stadium </strong>
        </span>
      </div>
    </div>
    <div class="play">
      <div class="container-top">
        <div class="row justify-content-md-center">
          <span class="col-md-auto"><img src="../../assets/club-1.png" alt="club"><strong>Spezia Young</strong> </span>
          <h2 class="col-md-auto" >vs</h2>
          <span class="col-md-auto"><strong>Monza Sport</strong> <img src="../../assets/club-6.png" alt="club"></span>
        </div>
      </div>
      <div class="container-bottom">
        <span><strong>
          <i class="fa-sharp fa-regular fa-calendar-days"></i> May 21, 2022 18:05 pm
          <i class="fa-solid fa-circle-plus"></i> Expert Stadium </strong>
        </span>
      </div>
    </div>
    <div class="play">
      <div class="container-top">
        <div class="row justify-content-md-center">
          <span class="col-md-auto"><img src="../../assets/club-7.png" alt="club"><strong>Geova Football</strong> </span>
          <h2 class="col-md-auto" >vs</h2>
          <span class="col-md-auto"><strong>Sampdoria Sports </strong> <img src="../../assets/club-8.png" alt="club"></span>
        </div>
      </div>
      <div class="container-bottom">
        <span><strong>
          <i class="fa-sharp fa-regular fa-calendar-days"></i> May 21, 2022 18:05 pm
          <i class="fa-solid fa-circle-plus"></i> Expert Stadium </strong>
        </span>
      </div>
    </div>
    <div class="play">
      <div class="container-top">
        <div class="row justify-content-md-center">
          <span class="col-md-auto"><img src="../../assets/club-9.png" alt="club"><strong>S.S.Lazio</strong> </span>
          <h2 class="col-md-auto" >vs</h2>
          <span class="col-md-auto"><strong>Rome</strong> <img src="../../assets/club-11.png" alt="club"></span>
        </div>
      </div>
      <div class="container-bottom">
        <span><strong>
          <i class="fa-sharp fa-regular fa-calendar-days"></i> May 21, 2022 18:05 pm
          <i class="fa-solid fa-circle-plus"></i> Expert Stadium </strong>
        </span>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .back{
    color: white;
    padding: 20px;
    background-image: url(../../assets/saha.jpg);
    background-repeat: no-repeat;
    background-position: center; 
    background-size: auto 100%;
}
    h2{
      padding: 20px;
    }
    .container-top{
      margin: 0 15px 0px;
    .row{
      background-color: rgba(0, 0, 0, 0.123);
      font-size: 30px;
      text-align: center;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      align-items: center;
      margin: 0 15px 0px;
        span{
          img{
            width: 130px;
          }
        }
    }
  }
  .play{
    margin-top: 20px;
    margin-bottom: 20px;
  }
  .container-bottom{
    background-color: rgba(0, 0, 0, 0.507);
    margin: 0 30px 0px;
    display: flex;
    justify-content: center;
    font-size: 12px;
    span{
      margin: 0 15px 0px;
      i{
        margin-right: 5px;
        margin-left: 20px;
      }
    }
  }
  
</style>