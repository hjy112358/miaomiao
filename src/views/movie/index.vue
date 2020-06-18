<template>
  <div id="main">
    <Header title="我的movie" />
    <div id="content">
      <router-link tag='div' to='/movie/city' class="list">城市</router-link>
      <router-link tag='div' to='/movie/nowplaying' class="list">正在热映</router-link>
      <router-link tag='div' to='/movie/comingsoon' class="list">即将上映</router-link>
      <router-link tag='div' to='/movie/search' class="list">搜索</router-link>
      <keep-alive>
        <!-- 缓存 -->
        <router-view />
      </keep-alive>
    </div>

    <tabar />
  </div>
</template>

<script>
import Header from "@/components/Header";
import tabar from "@/components/tabar";
export default {
  name: "movie",
  components: {
    Header,
    tabar
  }
};
</script>
<style  scoped>
  #content .list.router-link-active{
    color:#f00
  }
</style>>
