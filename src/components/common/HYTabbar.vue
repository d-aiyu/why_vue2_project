<template>
<div id="tab-bar" >
  <div class="tab-bar">首页</div>
  <div class="tab-bar">分类</div>
  <div class="tab-bar">购物车</div>
  <div class="tab-bar">我的</div>
</div>
</template>

<script>
  export default {
    
  }
</script>

<style scoped>
#tab-bar{
  display: flex;
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
}
.tab-bar{
  flex: 1;
  text-align: center;
  height: 49px;
  line-height: 49px;
  box-shadow: 0 -1px 0 0 rgba(66,66,66,0.1);
  


}
</style>