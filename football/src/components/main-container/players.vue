
<script>
export default {
  name: 'article',
}
</script>
<template>
  <div class="back">
    <div class="container-top text-center">
      <h3>Players</h3> 
    </div>
    <div class="container-card">
        <div class="card-box">
          <div class="players">
            <div class="image">
              <img src="../../assets/player1.jpg" alt="player">
              <div class="caption">

              </div>
            </div>
          </div>
        </div>
    </div>
    <div class="container-bottom">
      <a href="#">
        <button>
          View All Players
        </button>
      </a>
    </div>
  </div>
</template>

<style lang="scss" scoped>

.back{
  padding: 40px;
  background-image: url(../../assets/player.jpg);
  background-repeat: no-repeat;
  color: white;
  .container-bottom{
  display: flex;
  justify-content: center;
  button{
    width: 100%;
    height: 190%;
    background: #000;
    color: #ffffff;
    border: 1px solid white;
    padding: 0px 25px;
    border-radius: 2rem;
  }
}
.container-card{
  .card-box{
    width: 100%;
    display: flex;
    flex-wrap: wrap;
    text-align: center;
    border-radius: 3rem;
  }
}
}

</style>