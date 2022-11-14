<template>
  <div id="app">
    <router-view></router-view>
     <tab-bar>
       <tab-bar-item path="/home" active-color="blue">
         <img slot="item-icon" src="./assets/image/tabbar/home.png" alt="">
         <img slot="item-icon-active" src="./assets/image/tabbar/home-active.png" alt="">
         <div slot="item-text">首页</div>
       </tab-bar-item>
       <tab-bar-item path="/category" active-color="blue">
         <img slot="item-icon" src="./assets/image/tabbar/home.png" alt="">
         <img slot="item-icon-active" src="./assets/image/tabbar/home-active.png" alt="">
         <div slot="item-text">首页2</div>
       </tab-bar-item>
     </tab-bar>
  </div>
</template>

<script>
import TabBar from './components/tabbar/TabBar'
import TabBarItem from './components/tabbar/TabBarItem'
export default {
  name: 'App',
  components: {
    TabBar,
    TabBarItem
  }
}
</script>

<style>
  @import "./assets/css/base.css";
</style>
