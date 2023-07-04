<template>
  <div class="aboutus-main">
    <div class="main-header">
      <div class="fl">
        关于我们
      </div>
      <div class="fr">
        About us
      </div>
    </div>
    <div class="main-body">
      <div class="main-text">
        我们公司拥有10万+的高精尖人才库，为企
        业提供人才咨询、人才服务和项目申报。经
        过不断地坚持和努力，目前已服务客户120
        家+，深受企业信任和好评。我们郑重承
        诺，每一次合作都保证您满意为主，欢迎各
        界朋友业务洽谈。
      </div>
    </div>
    <div class="main-footer">
      <div>
        <a href="#">
          <div class="footer-title">
            联系我们 >>
          </div>
          <div class="footer-text">
            Contact us immediately
          </div>
        </a>
      </div>
    </div>
    <div class="aboutus-pic">
      <img src="../assets/images/aboutus-pic.png" alt="联系我们">
    </div>
  </div>
</template>
<style lang="scss" scoped>
.aboutus-main {
  max-width: 1280px;
  margin: 50px auto;
  box-sizing: border-box;
  position: relative;
  .main-header{
    overflow: hidden;
    height: 160px;
    .fl{
      float: left;
      color: #065DC8;
      text-align: left;
      font-size: 38px;
      font-weight: 700;
      line-height: 160px;
    }
    .fr{
      font-size: 20px;
      float: right;
      color: #065DC8;
      text-align: right;
      line-height: 100px;
    }
  }


  .main-body{
    .main-text{
      width: 540px;
      text-align: justify;
      font-size: 28px;
      line-height: 64px;
    }
  }

  .main-footer{
    padding: 50px;
    box-sizing: border-box;
    text-align: left;
    color: #ffffff;
    height: 170px;
    background-color: #0962CB;
    a{
      display: block;
      color: #fff;
      .footer-title{
        font-size: 20px;
        font-weight: 700;
      }
      .footer-text{
        font-size: 18px;
      }
    }
  }

  .aboutus-pic{
    position: absolute;
    top: 160px;
    right: 0px;
  }
}
</style>
<script setup>
</script>