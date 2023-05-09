<script>
export default {
  name : 'header'
}
</script>

<template>
  <div class="header">
    <div class="container d-flex">
    <div class="top-bar">
      <div class="logo-left">
        <a href="">
          <img src="../assets/sponsor1.png" alt="sponsor-1">
        </a>
        <a href="">
          <img src="../assets/sponsor2.png" alt="sponsor-2">
        </a>
      </div>
    </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>

.header{
  height: 100vh;
  background-image: url(../assets/slider1-1.jpg);
}
.container{
  align-items: center;
  height: 30%;
  flex-wrap: wrap;
  background-color: rgba(0, 0, 0, 0.315);
  max-width: 100%;
}
</style>