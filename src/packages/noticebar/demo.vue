<template>
  <div class="demo-list">
    <h4>默认用法</h4>
    <nut-noticebar
      text="华为畅享9新品即将上市，活动期间0元预约可参与抽奖，赢HUAWEI WATCH等好礼，更多产品信息请持续关注！"
    ></nut-noticebar>
    <h4>禁用滚动</h4>
    <nut-noticebar
      text="华为畅享9新品即将上市，活动期间0元预约可参与抽奖，赢HUAWEI WATCH等好礼，更多产品信息请持续关注！"
      :scrollable="false"
    ></nut-noticebar>
    <h4>通告栏模式--关闭模式</h4>
    <nut-noticebar
      :mode="true"
      @click="hello"
    >华为畅享9新品即将上市，活动期间0元预约可参与抽奖，赢HUAWEI WATCH等好礼，更多产品信息请持续关注！
    </nut-noticebar>
    <h4>通告栏模式--链接模式</h4>
    <nut-noticebar
      text="华为畅享9新品即将上市，活动期间0元预约可参与抽奖，赢HUAWEI WATCH等好礼，更多产品信息请持续关注！"
      left-icon="//img.yzcdn.cn/vant/volume.png"
    >
      <a href="https://www.jd.com">京东商城</a>
    </nut-noticebar>
  </div>
</template>

<script>
export default {
  methods: {
    hello() {
      console.log("hello world");
    }
  }
};
</script>

<style lang="scss" scoped>
</style>
