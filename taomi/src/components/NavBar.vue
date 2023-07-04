<template>
  <div class="nav-main">
    <ul>
      <li>首页</li>
      <li>产品与服务</li>
      <li>服务保障</li>
      <li>关于我们</li>
      <li>咨询客服</li>
    </ul>
  </div>
</template>
<style lang="scss" scoped>
  .nav-main{
    background-color: #0962CB;
    width: 100%;
    height: 35px;
    ul{
      max-width: 1280px;
      margin: 0 auto;
      list-style:none;
      display: flex;
      display: -webkit-flex; /* Safari */
      align-items: center;
      li{
        display: flex;
        display: -webkit-flex; /* Safari */
        flex: 1;
        align-content: space-around;

        color: #ffffff;
        text-align: center;
        height: 35px;
        line-height: 35px;
      }
    }
  }
  </style>