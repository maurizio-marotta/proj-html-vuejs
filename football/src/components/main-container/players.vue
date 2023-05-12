
<script>
export default {
  name: "article",
};
</script>
<template>
  <div class="back">
    <div class="container-top text-center">
      <h3>Players</h3>
    </div>
    <div class="container-card d-flex">
      <div class="card-box">
        <div class="players">
          <div class="image">
            <img src="../../assets/player1.jpg" alt="player" />
            <div class="caption ">
              <div class="number d-flex"><strong>19</strong></div>
              <div class="position d-flex">Giovanni Gattuso - Att</div>
            </div>
          </div>
        </div>
      </div>
      <div class="card-box">
        <div class="players">
          <div class="image">
            <img src="../../assets/player3.jpg" alt="player" />
            <div class="caption ">
              <div class="number d-flex"><strong>22</strong></div>
              <div class="position d-flex">Giuseppe Donnarumma - Por</div>
            </div>
          </div>
        </div>
      </div>
      <div class="card-box">
        <div class="players">
          <div class="image">
            <img src="../../assets/player4.jpg" alt="player" />
            <div class="caption ">
              <div class="number d-flex"><strong>39</strong></div>
              <div class="position d-flex">Danilo Barella</div>
            </div>
          </div>
        </div>
      </div>
      <div class="card-box">
        <div class="players">
          <div class="image">
            <img src="../../assets/player5.jpg" alt="player" />
            <div class="caption ">
              <div class="number d-flex"><strong>07</strong></div>
              <div class="position d-flex">Cristiano Rolando - Att</div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container-bottom">
      <a href="#">
        <button>View All Players</button>
      </a>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.back {
  padding: 40px;
  background-image: url(../../assets/player.jpg);
  background-repeat: no-repeat;
  color: white;
  .container-top{
    margin-bottom: 50px;
  }
  .container-bottom {
    display: flex;
    justify-content: center;
    button {
      width: 100%;
      height: 190%;
      background: #000;
      color: #ffffff;
      border: 1px solid white;
      padding: 0px 25px;
      border-radius: 2rem;
    }
  }
  .container-card {
    .card-box {
      width: 100%;
      display: flex;
      flex-wrap: wrap;
      text-align: center;
      .players {
        .image {
          margin: 0px 20px 0px 20px;
          img {
            width: 280px;
            border-radius: 3rem;
            position: relative;
            transition: all .2s ease-in-out;
            &:hover{
              cursor: pointer;
              transform: scale(1.1); 
            }
          }
          .caption {
            height: 90px;
            position: relative;
            top: -60px;
            border-radius: 3rem;
            color: #fff;
            background: #000000;
            text-align: center;
            padding: 18px;
            z-index: 1;
            transition: all .2s ease-in-out;
            &:hover{
              cursor: pointer;
              transform: scale(1.1); 
            }
            .number{
              justify-content: center;
              font-size: 20px;
            }
            .position{
              justify-content: center;
              color: #A7A7A7;
            }
          }
        }
      }
    }
  }
}
</style>