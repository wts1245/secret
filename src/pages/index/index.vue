<template>
  <div>
    <div class="list">
    <van-tabs sticky custom-class="custom" swipe-threshold="4" line-height="1px" tab-active-class="active" active="active" @change="onChange">
      <van-tab title="推荐">内容 1</van-tab>
      <van-tab title="朋友">内容 2</van-tab>
      <van-tab title="婚姻">内容 3</van-tab>
      <van-tab title="生活">内容 4</van-tab>
      <van-tab title="恋情">内容 5</van-tab>
    </van-tabs>
    </div>
  </div>
</template>
<script>
  export default {
  data(){
    return{
      active: 0
    }
  },
    methods:{
      onChange(event) {
        console.log(event)
      }
    }
  }
</script>
<style>
page{
  background: aliceblue;
}
.van-tabbar-item--active {
  color: #e10f02;
}
  .list{
    margin-top: 30rpx;
  }
  .tab{
    background: #E8F1C9;
    font-family:隶书;
    font-size: 20rpx;
  }
  .custom{
    width: 90%;
    border-radius: 20%;
    margin-left: 5%;
  }
</style>
