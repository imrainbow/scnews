<template>
  <div id="app">
    <h1>赛诚科技</h1>
    <i class="iconfont">&#xe60f;</i>
    <i class="iconfont sc-lishi"></i>
    <i class="iconfont">&#xe610;</i>
    <i class="iconfont sc-shoucang"></i>
    <i class="iconfont">&#xe611;</i>
    <i class="iconfont sc-shouye"></i>
    <i class="iconfont">&#xe613;</i>
    <i class="iconfont sc-sousuo"></i>
    <van-button type="primary">主要按钮</van-button>
    <van-button type="info">信息按钮</van-button>
    <van-button type="default">默认按钮</van-button>
    <van-button type="warning">警告按钮</van-button>
    <van-button type="danger">危险按钮</van-button>
    <div class="box">

    </div>
    <router-view></router-view>
  </div>
</template>

<style lang="less">
.box {
  background-color: aqua;
  width: 100px;
  height: 100px;
}

</style>
