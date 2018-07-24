<template>
  <div>
    <div class="container">
      <div class="userinfo">
        <img :src="avator" alt="">
        <p>Yosef Yuan</p>
        <YearProgress></YearProgress>
        <button class='btn'>添加图书</button>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data(){
    return {
      avator: require('@/assets/userinfo/yosef.jpeg'),
    }
  }
}
</script>

<style lang="scss">
.container{
  padding:0 30rpx;

}  
.userinfo{
  margin-top:100rpx;
  text-align:center;
  img{
    width: 150rpx;
    height:150rpx;
    margin: 20rpx;
    border-radius: 50%;
  }
}
</style>