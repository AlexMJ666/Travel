<template>
  <div>
    <div class="header">
      <div class="header-left">
        <div class="iconfont back-icon">&#xe624;</div>
      </div>
      <div class="header-input">
        <span class="iconfont">&#xe649;</span>
        输入城市/景点/游玩主题</div>
      <div class="header-right">
        城市
        <span class="iconfont arrow-icon">&#xe6aa;</span>
      </div>
    </div>

  </div>
</template>
<script>

  export  default {
    name: 'HomeHeader'
  }
</script>

<style lang="stylus" scoped>
  @import "~styles/varibles.styl"
  .header
    display :flex
    line-height: .86rem
    background $bgColor
    color white
    .header-left
      width: .64rem
      float: left
      .back-icon
        text-align center
        font-size .4rem
    .header-input
      flex: 1
      background white
      border-radius .1rem
      margin-top .12rem
      margin-left .2rem
      margin-right .2rem
      color #cacaca
      height .64rem
      line-height .64rem
      padding-left .2rem
    .header-right
      width: 1.24rem
      float: right
      text-align center
      .arrow-icon
        font-size .34rem
        margin-left: -.1rem
        text-align center

</style>
