<template>
  <div class="search">
    <input type="text" placeholder="输入关键词搜索">
    <button>谷歌搜索</button>
    <button>百度一下</button>
    <button>电影搜索</button>
    <button>磁力搜索</button>
    <button>老司机在线</button>
  </div>
</template>

<script>
  export default {
    name: 'Search'
  }
</script>

<style scoped lang="stylus">
@import '../common/stylus/mixins.styl'
@import '../common/stylus/variable.styl'
.search
  display flex
  width 100%
  justify-content center

  input 
    width 300px
    bdRadius(4px)
    padding-left 10px
    
  button
    bdRadius(4px)
    padding(5px 10px)
    background $btn-color
    cursor pointer
    color #fff
    margin-left 10px

  
</style>