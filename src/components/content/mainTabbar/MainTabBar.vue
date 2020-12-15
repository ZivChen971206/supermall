<template>
  <tab-bar>
    <tab-bar-item path="/home" activeColor="deeppink">
      <img slot="item-icon" src="~assets/img/tabbar/home.svg" alt="" />
      <img
        slot="item-icon-active"
        src="~assets/img/tabbar/home_active.svg"
        alt=""
      />
      <div slot="item-text">首页</div>
    </tab-bar-item>
    <tab-bar-item path="/category" activeColor="deeppink">
      <img slot="item-icon" src="~assets/img/tabbar/category.svg" alt="" />
      <img
        slot="item-icon-active"
        src="~assets/img/tabbar/category_active.svg"
        alt=""
      />
      <div slot="item-text">分类</div>
    </tab-bar-item>
    <tab-bar-item path="/cart" activeColor="deeppink">
      <img slot="item-icon" src="~assets/img/tabbar/cart.svg" alt="" />
      <img
        slot="item-icon-active"
        src="~assets/img/tabbar/cart_active.svg"
        alt=""
      />
      <div slot="item-text">购物车</div>
    </tab-bar-item>
    <tab-bar-item path="/profile" activeColor="deeppink">
      <img slot="item-icon" src="~assets/img/tabbar/profile.svg" alt="" />
      <img
        slot="item-icon-active"
        src="~assets/img/tabbar/profile_active.svg"
        alt=""
      />
      <div slot="item-text">我的</div>
    </tab-bar-item>
  </tab-bar>
</template>

<script>
import TabBar from "components/common/tabbar/TabBar";
import TabBarItem from "components/common/tabbar/TabBarItem";
export default {
  name: "MainTabBar",
  components: {
    TabBar,
    TabBarItem,
  },
};
</script>

<style>
</style>