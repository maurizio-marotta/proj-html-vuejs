
<script>
export default {
  name: 'article',
}
</script>


<template>

  <div>
    <div class="container-top">
      <div class="row justify-content-md-center">
        <span class="col-md-auto"><strong>Istanbul Sports </strong> <img src="../../assets/club-1.png" alt="club"></span>
        <h3 class="col-md-auto" >vs</h3>
        <span class="col-md-auto"><img src="../../assets/club-2.png" alt="club"><strong>United Fs Club</strong> </span>
      </div>
    </div>
    <div class="container-center">
      <span><strong>
        <i class="fa-sharp fa-regular fa-calendar-days"></i> May 21, 2022 18:05 pm
        <i class="fa-solid fa-circle-plus"></i> Expert Stadium </strong>
      </span>
    </div>
    <div class="container-bottom">
      <a href="#">
        <button>
          View Match Details
        </button>
      </a>
    </div>
  </div>

</template>

<style lang="scss" scoped>
  .container-top{
    .row{
      text-align: center;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      align-items: center;
      margin: 0 15px 20px;
        span{
          img{
            width: 80px;
          }
        }
    }
  }
  .container-center{
    display: flex;
    justify-content: center;
    font-size: 12px;
    i{
      margin-right: 5px;
      margin-left: 20px;
    }
  }
  .container-bottom{
    margin: 40px;
    display: flex;
    justify-content: center;
    button{
      width: 100%;
      height: 190%;
      background: #000;
      color: #ffffff;
      border: 1px solid;
      padding: 0px 25px;
      border-radius: 2rem;
    }
  }
</style>