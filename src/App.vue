<template>
  <div class="app">
    <!-- hearder  -->
     <!-- <img src="./assets/logo.png">
    <router-view/>-->
    <van-nav-bar
      title="标题"
      left-text="返回"
      left-arrow
    />
    <div>content内容区</div>
   
    <van-tabbar v-model="active" fixed>
      <van-tabbar-item icon="home-o">首页</van-tabbar-item>
      <van-tabbar-item icon="contact" >会员</van-tabbar-item>
      <van-tabbar-item icon="shopping-cart-o" info="0">购物车</van-tabbar-item>
      <van-tabbar-item icon="search" >搜索</van-tabbar-item>
    </van-tabbar>
  </div>
</template>

<script>
export default {
  name: "App",
  data:()=>({
    active:0
  }),
  methods:{
    
  }
};
</script>

<style>
/* #app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
