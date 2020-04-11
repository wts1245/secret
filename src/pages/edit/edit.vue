<template>
  <div>
    编辑
  </div>
</template>
<script>
  export default {
    data(){
      return{
        active:0
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
</style>
