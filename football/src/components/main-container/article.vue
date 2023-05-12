
<script>
export default {
  name: "article",
};
</script>
<template>
  <div>
    <div class="container-top">
      <div class="row">
        <div class="col-12 text-center">
          <span class="like"><i class="fa-solid fa-thumbs-up"></i></span>
          <h2>Resent New & Articles</h2>
          <p>Be aware of the football world.</p>
        </div>
      </div>
    </div>
    <div class="container-card">
      <div class="row">
        <div class="cards col-3">
          <div class="image d-flex">
            <img src="../../assets/news1-1.png" alt="" />
          </div>
          <span class="d-flex data">29.05.2022-football</span>
          <h4 class="d-flex title">What is Football</h4>
          <p class="d-flex article">Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti, ipsam.</p>
          <span class="button d-flex">
            <div class="more">more</div>
          </span>
        </div>
        <div class="cards col-3">
          <div class="image d-flex">
            <img src="../../assets/news2-1.png" alt="" />
          </div>
          <span class="d-flex data">29.05.2022-football</span>
          <h4 class="d-flex title">What is Football</h4>
          <p class="d-flex article">Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti, ipsam.</p>
          <span class="button d-flex">
            <div class="more">more</div>
          </span>
        </div>
        <div class="cards col-3">
          <div class="image d-flex">
            <img src="../../assets/news3-1.png" alt="" />
          </div>
          <span class="d-flex data">29.05.2022-football</span>
          <h4 class="d-flex title">What is Football</h4>
          <p class="d-flex article">Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti, ipsam.</p>
          <span class="button d-flex">
            <div class="more">more</div>
          </span>
        </div>
        <div class="cards col-3">
          <div class="image d-flex">
            <img src="../../assets/news4-1.png" alt="" />
          </div>
          <span class="d-flex data">29.05.2022-football</span>
          <h4 class="d-flex title">What is Football</h4>
          <p class="d-flex article">Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti, ipsam.</p>
          <span class="button d-flex">
            <div class="more">more</div>
          </span>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.cards{
  background-color: white;
  box-shadow: inset -5px 0px 0px 5px #dedede;
  border-radius: 20px;
}
.container-top {
  margin-top: 100px;
  .like {
    font-size: 50px;
    background-color: black;
    padding: 30px 42px;
    border-radius: 100px;
    color: white;
  }
  h2 {
    margin-top: 40px;
    font-size: 30px;
  }
  p {
    color: gray;
  }
}
.container-card {
  .row{
    padding: 30px;
    .image {
      justify-content: center;
      img {
        width: 70%;
        padding: auto;
      }
    }
    .data{
      justify-content: center;
    }
    .article{
      justify-content: center;
      color: gray;
    }
    .title{
      justify-content: center;
    }
    .button{
      justify-content: center;
      .more{
        background-color: black;
        color: white;
        padding: 20px 40px;
        border-radius: 50px;
        margin-bottom: 35px;
        margin-top: 10px;
      }
    }
  }
}
</style>