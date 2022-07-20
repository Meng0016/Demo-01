<template>
<div>
  <el-menu
      style="width:100%;height: 40px"
      :default-active="activeIndex2"
      class="el-menu-demo"
      mode="horizontal"
      background-color="#F5F5F5"
      text-color="6C6C6C"
      active-text-color="#d9631e"
      @select="handleSelect"
  >
    <el-menu-item index="1">商城首页</el-menu-item>
    <el-sub-menu index="2">
      <template #title>我的商城</template>
      <el-menu-item index="2-1">已买商品</el-menu-item>
      <el-menu-item index="2-2">我的足迹</el-menu-item>
      <el-menu-item index="2-3">我的上新</el-menu-item>
    </el-sub-menu>
    <el-sub-menu index="3">
      <template #title index="3-1">购物车</template>
    </el-sub-menu>
    <el-menu-item index="4">收藏夹</el-menu-item>
    <el-menu-item index="5">联系客服</el-menu-item>
    <el-menu-item index="6">请登录/注册</el-menu-item>
  </el-menu>
</div>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>

</style>