<template>
<div class="header">
  <div class="header-left">
    <div class="iconfont back-icon">&#xe682;</div>
  </div>
  <div class="header-input">
    <span class="iconfont">&#xe6f4;</span>
    请输入城市/景点/游玩主题</div>
  <div class="header-right">
    城市
    <span class="iconfont arrow-icon">&#xe64a;</span>
  </div>
</div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
  @import "~styles/varibles.styl"
.header
  display: flex
  line-height: .86rem
  background :$bgColor
  color :#ffffff
  .header-left
    width:.64rem
    float: left
    .back-icon
      text-align:center
      font-size : .4rem
  .header-input
    padding-left :.1rem
    flex:1
    background :#ffffff
    border-radius:.1rem
    height :.64rem
    line-height :.64rem
    margin-top :.12rem
    margin-left :.2rem
    color :#ccc
  .header-right
    width :1.24rem
    float :right
    text-align center
    .arrow-icon
      margin-left :.04rem
      font-size :.24rem
</style>
