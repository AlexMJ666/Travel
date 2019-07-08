<template>
  <div>
    <div class="header">
      <div class="header-left">返回</div>
      <div class="header-input">输入城市/景点/游玩主题</div>
      <div class="header-right">城市</div>
    </div>

  </div>
</template>
<script>

  export  default {
    name: 'HomeHeader'
  }
</script>

<style lang="stylus" scoped>
  .header
    display :flex
    line-height: 2.86rem
    background #25a4bb
    color white
    .header-left
      width: 2.64rem
      float: left
    .header-input
      flex: 1
      background white
      border-radius .2rem
      margin-top .42rem
      margin-left .8rem
      margin-right .8rem
      color #cacaca
      height 2rem
      line-height 2rem
    .header-right
      width: 2.24rem
      float: right
      text-align center
</style>
