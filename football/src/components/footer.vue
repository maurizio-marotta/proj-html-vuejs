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
        <div class="social d-flex">
          <a href="#" class="borders"
            ><i class="fa-brands fa-square-facebook"></i
          ></a>
          <a href="#" class="borders"><i class="fa-brands fa-instagram"></i></a>
          <a href="#" class="borders"><i class="fa-brands fa-twitter"></i></a>
        </div>
      </div>
      <div class="col-5 subscribe">
        <h5>Join Our Newsletter</h5>
        <div class="join">
          Subscribe to be informed about important developments in our club and
          football world.
        </div>
        <div>
          <input class="search" type="text" placeholder="Your Email Address" />
        </div>
        <div>
          <button>subscribe</button>
        </div>
      </div>
      <div class="col-2 info">
        <h5>Education</h5>
        <ul>
          <li>FIXTURES & RESULTS</li>
          <li>EAGUE TABLE</li>
          <li>PLAYERS</li>
          <li>GALLERY</li>
        </ul>
      </div>
      <div class="col-2 info">
        <h5>Quick Links</h5>
        <ul>
          <li>FIXTURES & RESULTS</li>
          <li>EAGUE TABLE</li>
          <li>PLAYERS</li>
          <li>GALLERY</li>
        </ul>
      </div>
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
    i {
      margin-right: 10px;
    }
    .logo-container {
      margin-bottom: 15px;
      & img {
        width: 40px;
      }
    }

    .position {
      margin-bottom: 10px;
    }

    .call {
      margin-bottom: 10px;
    }

    .email {
      margin-bottom: 10px;
    }
    .social {
      text-align: center;
      font-size: 20px;
      gap: 5px;
      a {
        flex: 1;
      }
      i {
        margin: 0;
        color: white;
      }
    }
  }
  .subscribe {
    input {
      width: 100%;
      height: 50px;
      padding: 0 30px;
      background: #fff;
      border-radius: 2rem;
      margin-bottom: 5px;
    }
    .join {
      font-size: 12px;
      margin-bottom: 15px;
    }
    button {
      width: 100%;
      line-height: 50px;
      display: inline-block;
      background: #fff;
      border: 1px solid;
      padding: 0 30px;
      position: relative;
      font-size: 17px;
      border-radius: 2rem;
    }
  }
  .info {
    ul {
      margin-left: -30px;
      &:hover {
        cursor: pointer;
      }
    }
    li {
      width: 100%;
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      margin: 0;
      padding: 5px 0;
      list-style: none;
      font-size: 7px;
      &::before {
        content: "";
        width: 11px;
        height: 4px;
        display: inline-block;
        background: #ffffff;
        margin-right: 9px;
      }
    }
  }
}
.copy {
  font-size: 11px;
}

.borders {
  border: 1px solid white;
}
.borders:hover{
    border: 1px solid rgba(128, 128, 128, 0);
    transition: .5s;
  }

</style>