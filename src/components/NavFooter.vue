<!--  -->
<template>
  <div class="footer">
    <div class="footer-logo">
      <img src="../../public/imgs/logo-footer.png" alt="">
      <p>小米商城</p>
    </div>
    <div class="footer-link">
      <a href="">小米商城</a><span>|</span>
      <a href="">MIUI</a><span>|</span>
      <a href="">米家</a><span>|</span>
      <a href="">米聊</a><span>|</span>
      <a href="">多看</a><span>|</span>
      <a href="">游戏</a><span>|</span>
      <a href="">政企服务</a><span>|</span>
      <a href="">小米天猫店</a>
    </div>
    <div class="copyRight">© mi.com 京ICP证110507号 京ICP备10046444号 京公网安备11010802020134号 京网文[2020]0276-042号</div>
  </div>
</template>

<script>
export default {
  name: "nav-footer",
  data() {
    return {};
  },
  //生命周期 - 创建完成（访问当前this实例）
  created() {},
  //生命周期 - 挂载完成（访问DOM元素）
  mounted() {}
};
</script>
<style lang="scss" scoped>
/* @import url(); 引入css类 */
.footer{
  height: 234px;
  border-top: 4px solid #FF6600;
  background-color: #333333;
  color: #999999;
  font-size: 16px;
  text-align: center;
  .footer-logo{
    margin-top: 46px;
    margin-bottom: 31px;
    img{
      width: 53px;
      height: 36px;
      margin-bottom: 13px;
    }

  }
  .footer-link{
    a{
      color: #999999;
      display: inline-block;
    }
    span{
      margin: 0 10px;
    }
    margin-bottom: 13px;
  }

}
</style>