<template>
  <div class="app">
    <van-nav-bar title="发现" class="topNav">
      <template #right>
        <van-icon name="search" color="black" />
        <van-icon name="add-o" color="black" />
      </template>
    </van-nav-bar>

    <van-nav-bar class="friden">
      <template #left>
        <van-icon name="smile-o" color="black" />
        <span>朋友圈</span>
      </template>
      <template #right>
        <van-icon name="arrow" color="#A8A8A8" />
      </template>
    </van-nav-bar>

    <van-nav-bar>
      <template #left>
        <van-icon name="smile-o" color="black" />
        <span>视频号</span>
      </template>
      <template #right>
        <van-icon name="arrow" color="#A8A8A8" />
      </template>
    </van-nav-bar>

    <van-nav-bar class="friden">
      <template #left>
        <van-icon name="smile-o" color="black" />
        <span>直播</span>
      </template>
      <template #right>
        <van-icon name="arrow" color="#A8A8A8" />
      </template>
    </van-nav-bar>

    <van-nav-bar>
      <template #left>
        <van-icon name="smile-o" color="black" />
        <span>扫一扫</span>
      </template>
      <template #right>
        <van-icon name="arrow" color="#A8A8A8" />
      </template>
    </van-nav-bar>

    <van-nav-bar class="friden">
      <template #left>
        <van-icon name="smile-o" color="black" />
        <span>摇一摇</span>
      </template>
      <template #right>
        <van-icon name="arrow" color="#A8A8A8" />
      </template>
    </van-nav-bar>

    <van-nav-bar class="friden">
      <template #left>
        <van-icon name="smile-o" color="black" />
        <span>搜一搜</span>
      </template>
      <template #right>
        <van-icon name="arrow" color="#A8A8A8" />
      </template>
    </van-nav-bar>

    <van-nav-bar class="friden">
      <template #left>
        <van-icon name="smile-o" color="black" />
        <span>附近</span>
      </template>
      <template #right>
        <van-icon name="arrow" color="#A8A8A8" />
      </template>
    </van-nav-bar>

    <van-nav-bar>
      <template #left>
        <van-icon name="smile-o" color="black" />
        <span>购物</span>
      </template>
      <template #right>
        <van-icon name="arrow" color="#A8A8A8" />
      </template>
    </van-nav-bar>

    <van-nav-bar class="friden">
      <template #left>
        <van-icon name="smile-o" color="black" />
        <span>游戏</span>
      </template>
      <template #right>
        <van-icon name="arrow" color="#A8A8A8" />
      </template>
    </van-nav-bar>

    <van-nav-bar>
      <template #left>
        <van-icon name="smile-o" color="black" />
        <span>小程序</span>
      </template>
      <template #right>
        <van-icon name="arrow" color="#A8A8A8" />
      </template>
    </van-nav-bar>

    <van-tabbar >
  <van-tabbar-item icon="home-o">标签</van-tabbar-item>
  <van-tabbar-item icon="search" dot>标签</van-tabbar-item>
  <van-tabbar-item icon="friends-o" badge="5">标签</van-tabbar-item>
  <van-tabbar-item icon="setting-o" badge="20">标签</van-tabbar-item>
</van-tabbar>
  </div>
</template>

<script>
import { Button, NavBar, Icon,Tabbar,TabbarItem  } from "vant";
export default {
  name: "HelloWorld",
  components: {
    [Button.name]: Button,
    [NavBar.name]: NavBar,
    [Icon.name]: Icon,
    [Tabbar.name]: Tabbar,
    [TabbarItem.name]: TabbarItem
  },
  methods: {},
};
</script>

<style scoped>
.friden{
  margin-bottom: 10px;
}
.app {
  height: 100%;
  background-color: #ededed;
}
.topNav {
  background-color: #ededed;
  height: 100px;
  width: 100%;
}
.van-icon {
  margin-right: 20px;
  font-size: 40px;
}
</style>
