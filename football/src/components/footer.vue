<script>
export default {
  name : 'footer'
}
</script>

<template>
  <div class="root p-4">
    <div class="row">
      <div class="col-3 contacts">
        <div class="logo-container">
          <img src="../assets/logo-footer-football.png" alt="">
        </div>
        <div class="position">ciao ciao</div>
        <div class="call">Lorem ipsum dolor sit amet consectetur adipisicing.</div>
        <div class="email">Lorem, ipsum dolor.</div>
        <div class="social">lore</div>
      </div>
      <div class="col-5"></div>
      <div class="col-2"></div>
      <div class="col-2"></div>
    </div>
  <div class="row copy text-center mt-3 text-white">
    <span>© 2023 Football Club - All Rights Reserved.</span>
  </div>
</div>
</template>

<style lang="scss" scoped>
  .root{
    background-image: url(../assets/footer-bg-football.jpg);
    .contacts{
      .logo-container{
        background-color: red;
      }
      .position{
        background-color: gray;
      }
      .call{
        background-color: aqua;
      }
      .email{
        background-color: green;
      }
      .social{
        background-color: blue;
      }
    }
  }
  .copy{
    font-size: 11px;
  }
</style>