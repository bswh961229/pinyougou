<template>
  <div>
    <div class="header">
      <icon type='search'></icon>
      <input type="text" placeholder="搜索">
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="less">
.header{
  background-color: #ff2d4a;
  padding:20rpx 16rpx;
  position: relative;
  icon{
  position: absolute;
  z-index: 998;
  top:30rpx;
  left:50%;
  transform: translateX(-200%);
  }
  input{
    text-align: center;
    background-color: #ffffff;
    height: 60rpx;
    border-radius: 20rpx;
    
  }
}
</style>
  

