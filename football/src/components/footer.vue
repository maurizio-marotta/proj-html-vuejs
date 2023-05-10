<script>
export default {
  name: "footer",
};
</script>

<template>
  <div class="root p-4 text-white">
    <div class="row">
      <div class="col-3 contacts">
        <div class="logo-container">
          <img src="../assets/logo-footer-football.png" alt="" />
        </div>
        <div class="position">
          <i class="fa-solid fa-location-dot"></i>New Jersey, USA
        </div>
        <div class="call">
          <i class="fa-solid fa-phone-volume"></i>+1 (234) 567 89 10
        </div>
        <div class="email">
          <i class="fa-solid fa-envelope"></i>example@example.com
        </div>
        <div class="social d-flex ">
          <a href="#" class="border"><i class="fa-brands fa-square-facebook"></i></a>
          <a href="#" class="border"><i class="fa-brands fa-instagram"></i></a>
          <a href="#" class="border"><i class="fa-brands fa-twitter"></i></a>
        </div>
      </div>
      <div class="col-5 subscribe">
        <h4>Join Our Newsletter</h4>
        <div>Subscribe to be informed about important developments in our club and football world.</div>
        <div>
          <input class="search" type="text" placeholder="Your Email Address">
        </div>
        <div></div>
      </div>
      <div class="col-2"></div>
      <div class="col-2"></div>
    </div>
    <div class="row copy text-center mt-3 text-white">
      <span>© 2023 Football Club - All Rights Reserved.</span>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.root {
  background-image: url(../assets/footer-bg-football.jpg);
  .contacts {
    i{
      margin-right: 10px;
    }
    .logo-container {
      margin-bottom: 15px;
      & img {
        width: 40px;
      }
    }

    .position{
      margin-bottom: 10px;
    }

    .call{
      margin-bottom: 10px;
    }

    .email{
      margin-bottom: 10px;
    }
    .social {
      text-align: center;
      font-size: 20px;
      gap: 5px;
      a{
        flex: 1;
        }
      i{
        margin: 0;
        color: white;
      }
      }
    }
    .subscribe{
      input{
        width: 100%;
        height: 30px;
      }
    }
  }
  .copy {
    font-size: 11px;
  }

</style>