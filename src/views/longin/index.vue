<template>
  <div class="longin-container">
    <!-- 头部导航 -->
    <van-nav-bar class="page-nav" title="登录"/>
    <!-- /头部导航 -->
    <!-- 表单验证 -->
    <van-form @submit="onSubmit">
  <van-field
    name="用户名"
    placeholder="请输入手机号"
  >
  <i slot="left-icon" class="iconfont sc-shouji" style="font-size: 37px"></i>
  </van-field>
  <van-field
    name="密码"
    placeholder="请输入验证码"
  >
  <i slot="left-icon" class="iconfont sc-yanzhengma" style="font-size: 37px"></i>
    <template #button>
    <van-button size="small" type="primary">发送验证码</van-button>
  </template>
  </van-field>
  <div class="btn-box" style="margin: 53px 28px">
    <van-button style="background-color: #6db4fb; border: none;"  block type="info" native-type="submit">提交</van-button>
  </div>
</van-form>

    <!-- /表单验证 -->
  </div>
</template>

<script>
export default {
  name: 'LonginPage',
  methods: {
    onSubmit (values) {
      console.log('submit', values)
    }
  }

}
</script>

<style scoped lang="less">
.longin-containe {

  .page-nav {
    .van-nav-bar__title {
      font-size: 32px;
    }
  }
  .iconfont {
    font-size: 37px !important;
  }

}

</style>
