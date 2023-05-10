<script>
export default {
  name: "header",
};
</script>

<template>
  <div class="header">
    <div class="container ">
      <div class="top-bar">
        <a href="" class="logo sponsor"><img src="../assets/sponsor1.png" alt=""></a>
        <a href="" class="logo sponsor"><img src="../assets/sponsor2.png" alt=""></a>
        <a href="" class="logo football"><img src="../assets/logo-football.png" alt=""></a>
        <a href="" class="logo social"><span><i class="fa-brands fa-facebook-f"></i></span></a>
        <a href="" class="logo social"><i class="fa-brands fa-instagram"></i></a>
        <a href="" class="logo social"><i class="fa-brands fa-twitter"></i></a>
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
</template>

<style lang="scss" scoped>
.header {
  flex-wrap: wrap;
  background-color: rgba(0, 0, 0, 0.315);
}

.container {
  justify-content: center;
  align-items: center;
  height: 30%;
}

.sponsor{
  margin-top: 5%;
}

.social{
  font-size: 20px;
  color: white;
  margin-top: 5%;
}
.logo{
  padding: 15px;
}

.football{
  width: 80%;
}

.bottom-bar{
  padding: 15px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.bottom-bar a{
  font-weight: bold;
  display: block;
  padding: 10px;
  font-size: 13px;
  text-decoration: none;
  color: white;
  &::after{
    content: '';
    height: 4px;
    width: 0%;
    transition: width 0.3s;
    display: block;
    background-color: white;
  }
  &:hover::after{
    width: 100%;
  }
}

</style>