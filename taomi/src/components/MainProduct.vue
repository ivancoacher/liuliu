<template>
  <div class="product-main">
    <div class="main-header">
      <img src="../assets/images/product.png" alt="产品与服务">
    </div>
    <div class="main-body">
      <div class="product-wrapper">
        <div class="product-item">

          <div class="item-icon"><img src="../assets/images/icon-11.png" alt="人才猎头"></div>
          <div class="item-icon">人才猎头</div>
          <div class="item-icon">10w+人才资源库</div>
        </div>
      </div>
      <div class="product-wrapper">

        <div class="product-item">
          <div class="item-icon"><img src="../assets/images/icon-11.png" alt="人才猎头"></div>
          <div class="item-icon">人才论坛</div>
          <div class="item-icon">各类线上线下招聘会</div>
        </div>
      </div>
      <div class="product-wrapper">

        <div class="product-item">
          <div class="item-icon"><img src="../assets/images/icon-11.png" alt="人才猎头"></div>
          <div class="item-icon">项目申报</div>
          <div class="item-icon">国家级项目申请支持</div>
        </div>
      </div>
      <div class="product-wrapper">

        <div class="product-item">
          <div class="item-icon"><img src="../assets/images/icon-11.png" alt="人才猎头"></div>
          <div class="item-icon">人才评审</div>
          <div class="item-icon">组织海内外专家评审</div>
        </div>
      </div>
      <div class="product-wrapper">
        <div class="product-item">
          <div class="item-icon"><img src="../assets/images/icon-11.png" alt="人才猎头"></div>
          <div class="item-key">人才培训</div>
          <div class="item-text">对个人/企业提供培训</div>
        </div>
      </div>
      <div class="product-wrapper">
        <div class="product-item">
          <div class="item-icon"><img src="../assets/images/icon-11.png" alt="人才猎头"></div>
          <div class="item-icon">其他服务</div>
          <div class="item-icon">更多合作方向探讨</div>
        </div>
      </div>
    </div>
    <div class="main-footer">
      <div class="footer-item">
        人才入驻 >&nbsp;&nbsp;&nbsp;&nbsp;|
      </div>
      <div class="footer-item">
        讲师入驻 >&nbsp;&nbsp;&nbsp;&nbsp;|
      </div>
      <div class="footer-item">
        企业合作 >
      </div>
    </div>
  </div>
</template>
<style lang="scss" scoped>
.product-main {
  .main-header {
    margin-top: 25px;
  }

  .main-body {
    margin: 0 auto;
    max-width: 1280px;
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    padding: 25px;
    align-content: space-between;

    .product-wrapper {
      background-color: #0E6FDF;
      width: 30%;
      padding: 5px;
      margin-bottom: 25px;
      border-radius: 5px;

      .product-item {
        border: 1px #fff solid;
        box-sizing: border-box;
        width: 100%;
        height: 100%;
        color: #fff;
        padding: 15px;

        .item-key {
          font-size: 20px;
          font-weight: 700;
        }

        .item-text {
          font-size: 16px;
        }
      }
    }

  }

  .main-footer{
    display: flex;
    justify-content: center;
    .footer-item{
      font-size: 30px;
      font-weight: 700;
      margin-right: 25px;
    }
  }
}
</style>
<script setup>
</script>