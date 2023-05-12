<script>
export default {
  name: "header",
};
</script>

<template>
  <div>
    <div class="slide">
      <div class="header">
        <div class="container d-flex">
          <div class="top-bar">
            <a href="" class="logo sponsor"
              ><img src="../assets/sponsor1.png" alt=""
            /></a>
            <a href="" class="logo sponsor nike"
              ><img src="../assets/sponsor2.png" alt=""
            /></a>
            <a href="" class="logo football"
              ><img src="../assets/logo-football.png" alt=""
            /></a>
            <a href="" class="logo social"
              ><span><i class="fa-brands fa-facebook-f"></i></span
            ></a>
            <a href="" class="logo social"
              ><i class="fa-brands fa-instagram"></i
            ></a>
            <a href="" class="logo social"
              ><i class="fa-brands fa-twitter"></i
            ></a>
          </div>
        </div>
        <div class="bottom-bar">
          <a href="#">HOME</a>
          <a href="#">FIXTURES & RESULTS</a>
          <a href="#">LEAGUE TABLE</a>
          <a href="#">PLAYERS</a>
          <a href="#">GALLERY</a>
          <a href="#">BLOG</a>
          <a href="#">CONTACT</a>
        </div>
      </div>
      <div class="title">
        <h1 class="text-center">Welcome to</h1><br>
        <h1 class="text-center title-2">FootBall Club</h1>
        <p class="text-center"> Private FootBall matches</p>
        <a href="#" class="d-flex">
        <button> Learn More<i class="fa-solid fa-arrow-right"></i></button>
        </a>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>

.slide{
  height: 90vh;
  color: white;
  background-image: url(../assets/slider1-1.jpg);
  background-position: center; 
  background-size: 100%;
  .title{
    margin: -65px 85px 0px 85px;
  }
  h1{
    font-size: 6rem;
  }
  .title-2{
    margin-top: -35px;
  }
  a{
    justify-content: center;
    text-decoration: none;
    button{
      background: #00000000;
      color: #ffffff;
      border: 1px solid white;
      padding: 20px 60px;
      border-radius: 2rem;
      i{
        font-size: 10px;
        margin-left: 5px;
      }
      }
    }
  }


.header {
  flex-wrap: wrap;
  background-color: rgba(0, 0, 0, 0.596);
  position: relative;
}

.container {
  justify-content: center;
  align-items: center;
  height: 30%;
}

.top-bar {
  margin-left: -110px;
}

.sponsor {
  margin-top: 5%;
}
.nike{
  margin-right: -65px;
  position: sticky;
  z-index: 1;
}

.social {
  font-size: 30px;
  color: white;
  margin-top: 5%;
}
.logo {
  padding: 15px;
}

.football {
  width: 80%;
}

.bottom-bar {
  margin: 0, auto;
  padding: 15px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.bottom-bar a {
  margin: 0px 30px 0px 30px;
  font-weight: bold;
  display: block;
  padding: 10px;
  font-size: 13px;
  text-decoration: none;
  color: white;
  &::after {
    content: "";
    height: 4px;
    width: 0%;
    transition: width 0.3s;
    display: block;
    background-color: white;
  }
  &:hover::after {
    width: 100%;
  }
}
</style>