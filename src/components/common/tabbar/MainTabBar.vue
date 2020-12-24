<template>
  <tab-bar>
    <tab-bar-item path="/home" activeColor="blue">
      <i slot="item-icon" class="fa fa-home"></i>
      <i slot="item-icon-active" class="fa fa-home"></i>
      <div slot="item-text">首页</div>
    </tab-bar-item>
    <tab-bar-item path="/category" activeColor="blue">
      <i slot="item-icon" class="fa fa-th-large"></i>
      <i slot="item-icon-active" class="fa fa-th-large"></i>
      <div slot="item-text">分类</div>
    </tab-bar-item>
    <tab-bar-item path="/cart" activeColor="blue">
      <i slot="item-icon" class="fa fa-shopping-cart"></i>
      <i slot="item-icon-active" class="fa fa-shopping-cart"></i>
      <div slot="item-text">购物车</div>
    </tab-bar-item>
    <tab-bar-item path="/profile" activeColor="blue">
      <i slot="item-icon" class="fa fa-user-o"></i>
      <i slot="item-icon-active" class="fa fa-user-o"></i>
      <div slot="item-text">我的</div>
    </tab-bar-item>
  </tab-bar>
</template>

<script>
  import TabBar from './TabBar'
  import TabBarItem from './TabBarItem'

  export default{
    name: "MainTabBar",
    components: {
      TabBar,
      TabBarItem
    }
  }
</script>

<style lang="less" scoped>
  @import "assets/css/fa/css/all.css";
</style>
