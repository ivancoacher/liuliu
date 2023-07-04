<template>
  <div class="service-main">
    <div class="main-header">
      <img src="../assets/images/service.png" alt="服务质量100%">
    </div>
    <div class="main-body">
      <div class="main-row">
        <div class="main-item">
          <img src="../assets/images/icon-1.png" alt="交付快">
          <div>
            <div class="item-key">交付快</div>
            <div class="item-text">最快8小时完成</div>
          </div>
        </div>
        <div class="main-item">
          <img src="../assets/images/icon-1.png" alt="方案定制">
          <div>
            <div class="item-key">方案定制</div>
            <div class="item-text">输出定制化方案</div>
          </div>
        </div>
        <div class="main-item">
          <img src="../assets/images/icon-1.png" alt="0差评">
          <div>
            <div class="item-key">0差评</div>
            <div class="item-text">一切为质量负责</div>
          </div>
        </div>
      </div>
      <div class="main-row">
        <img src="../assets/images/pic-1.png" alt="服务质量">
      </div>
      <div class="main-row">
        <div class="main-item">
          <img src="../assets/images/icon-2.png" alt="人才库丰富">
          <div>
            <div class="item-key">人才库丰富</div>
            <div class="item-text">海量的人才资源</div>
          </div>
        </div>
        <div class="main-item">
          <img src="../assets/images/icon-2.png" alt="专业团队">
          <div>
            <div class="item-key">专业团队</div>
            <div class="item-text">10年+行业经验</div>
          </div>
        </div>
        <div class="main-item">
          <img src="../assets/images/icon-2.png" alt="联系我们">
          <div>
            <div class="item-key">联系我们</div>
            <div class="item-text">客服在线</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style lang="scss" scoped>
.service-main {
  text-align: center;
  background-color: #f4f4f4;
  margin-top: 20px;
  .main-header{
    text-align: center;
    margin-top: 50px;
  }
  .main-body{
    margin: 0 auto;
    display: flex;
    max-width: 1280px;
    overflow: hidden;
    justify-content: center;
    .main-row{
      float: left;
      margin-right: 10px;
      box-sizing: border-box;
      .main-item{
        width: 340px;
        border: 1px #ccc dashed;
        margin-bottom: 42px;
        height: 150px;
        box-sizing: border-box;
        &>div{
          float: left;
          text-align: left;
          padding-top: 50px;
          margin-left: 10px;
          .item-key{
            color: #535353;
            font-size: 18px;
            font-weight: 700;
          }
          .item-text{
            color: #535353;

          }
        }
        img{
          float: left;
          margin-top: 25px;
          margin-left: 25px;
        }
      }
    }
  }
}
</style>
<script setup>
</script>