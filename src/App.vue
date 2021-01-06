<template>
  <div id="nav">
    <router-view />
    <van-tabbar route>
      <van-tabbar-item to="/">首页</van-tabbar-item>
      <van-tabbar-item to="/profile">课程表</van-tabbar-item>
      <van-tabbar-item to="/mine">我的</van-tabbar-item>
    </van-tabbar>
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
