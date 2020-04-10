<template>
 <div>
 <i-button type="primary" bind:click="handleClick">这是一个按钮</i-button>
 <i-card title="卡片标题" extra="额外内容" thumb="https://i.loli.net/2017/08/21/599a521472424.jpg">
    <view slot="content">内容不错</view>
    <view slot="footer">尾部内容</view>
</i-card>
 </div>    
</template>
<script>
    export default {
        
    }
</script>

  </div>  
</template>
<script>
export default {
  
  methods: {
    toOtherPage(){
      wx.navigateTo({
          url: '/pages/my/main'
})
    }
  },
}
</script>
<style>
page{
  background: #ECFAE2;
}
</style>