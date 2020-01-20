<!--  -->
<template>
  <div>
    <order-header></order-header>
    <router-view></router-view>
    <order-footer></order-footer>
  </div>
</template>

<script>
import OrderHeader from "../components/OrderHeader";
import OrderFooter from "../components/OrderFooter";

export default {
  name: "order",
  components: {
    OrderHeader,
    OrderFooter
  },
  data() {
    return {};
  },
  //生命周期 - 创建完成（访问当前this实例）
  created() {},
  //生命周期 - 挂载完成（访问DOM元素）
  mounted() {}
};
</script>
<style scoped>
/* @import url(); 引入css类 */
</style>