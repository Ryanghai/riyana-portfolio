<template>
  <div class="all-wrapper">
    <div class="top-image">
      <img src="../assets/top-image.png" alt="">
    </div>
    <div class="main-container">
      <div class="main-icon">
        <img src="../assets/icon.png" alt="">
      </div>
      <div class="main-text">
        <p class="name">Riyana Harima</p>
        <div class="introduce">
          <p>イラスト・映画が好きな20歳<br />エンジニア歴約1年半</p>
        </div>
      </div>
      <div class="main-sns">
        <div class="sns-title">
          <span>SNS</span>
        </div>
        <div class="sns-contents">
          <a href="https://twitter.com/RyangHai" class="item">
            <div class="sns-icon"><img src="../assets/twitter.svg" alt=""></div>
          </a>
          <a href="https://www.instagram.com/riyanar1t00/" class="item">
            <div class="sns-icon"><img src="../assets/whiteIG.svg" alt=""></div>
          </a>
        </div>
      </div>
      <div class="main-portfolio">
        <div class="portfolio-title">
          <span>Portfolio</span>
        </div>
        <div class="portfolio-contents">
          <a href="https://sugoi-mojiokoshi.varygoodkun.net" class="portfolio-item">
            <div class="portfolio-icon">
              <img src="../assets/icon.png" alt="">
              <p>すごい文字起こし<br>ばりぐっどくん</p>
            </div>
          </a>
          <a href="https://www.shigureni.com/" class="portfolio-item">
            <div class="portfolio-icon">
              <img src="../assets/icon.png" alt="">
              <p>shigureni<br>システム準備中…</p>
            </div>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans&display=swap');
.all-wrapper {
  font-family: 'Noto Sans', sans-serif;
}
.top-image {
  position: relative;
}
.top-image img{
  width: 100vw;
  height: auto;
  z-index: 2;
}

.main-container {
  position: absolute;
  z-index: 20;
  width: 100vw;
  margin-top: -40px;
  height: calc(100vh - 175px);
  background-color: #ffffff;
  border-radius: 20px 20px 0 0;
}

.main-icon img {
  width: 100px;
  height: 100px;
  margin-top: -50px;
  border: 2px solid #9893bd;
  border-radius: 50%;
}

.name {
  margin: 0;
  font-weight: bold;
  color: #221f38;
  font-size: 18px;
  margin-top: 20px;
}

.introduce p {
  margin: 0 auto;
  font-size: 14px;
  width: 70%;
  color: #545261;
  margin-top: 10px;
}

.main-sns {
  margin-top: 30px;
}

.sns-title span {
  font-weight: bold;
  border-bottom: 1px solid #221f38;
}

.sns-contents {
  overflow-x: auto;
  white-space: nowrap;
  -webkit-overflow-scrolling: touch;
}

.item {
  display: inline-block;
  margin: 16px 8px;
  background: #9893bd;
  border-radius: 50%;
}

.sns-icon {
  width: 55px;
  height: 55px;
}

.sns-icon img {
  width: 30px;
  height: 30px;
  margin: 12px -2px 0 0;
}

.main-portfolio {
  margin-top: 10px;
}

.portfolio-title span {
  font-weight: bold;
  border-bottom: 1px solid #221f38;
}

.portfolio-contents {
  overflow-x: auto;
  white-space: nowrap;
  -webkit-overflow-scrolling: touch;
}

.portfolio-item {
  display: inline-block;
  margin: 16px 8px;
  background: #9893bd;
  text-decoration: none;
}

.portfolio-icon {
  width: 124px;
  height: 93px;
  position: relative;
  margin: 0 auto;
  box-shadow: 5px 5px 15px #e3e3e3, -5px -5px 15px #fff;
}

.portfolio-icon img {
  width: 100%;
  height: 100%;
}

.portfolio-icon p {
  margin: 0;
  font-size: 14px;
  color: #545261;
}
</style>
