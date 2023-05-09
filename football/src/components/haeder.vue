<script>
export default {
  name: "header",
};
</script>

<template>
  <div class="header">
    <div class="container d-flex">
      <div class="top-bar">
        <a href="" class="logo"><img src="../assets/sponsor1.png" alt=""></a>
        <a href="" class="logo"><img src="../assets/sponsor2.png" alt=""></a>
        <a href="" class="logo"><img src="../assets/logo-football.png" alt=""></a>
        <a href="" class="logo social"><span><i class="fa-brands fa-facebook-f"></i></span></a>
        <a href="" class="logo social"><i class="fa-brands fa-instagram"></i></a>
        <a href="" class="logo social"><i class="fa-brands fa-twitter"></i></a>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.header {
  flex-wrap: wrap;
  background-color: rgba(0, 0, 0, 0.315);
}

.container {
  align-items: center;
  height: 30%;
}

.social{
  font-size: 30px;
}
</style>