<template>
  <div class="small-item">
    <ul class="item-wrap">
      <li>
        <img src="/img/1.png" alt="">
        <span>哔哩哔哩</span>
      </li>
      <li>
        <img src="/img/2.png" alt="">
        <span>ACFUnds</span>
      </li>
      <li>
        <img src="/img/3.png" alt="">
        <span>plxiv</span>
      </li>
      <li>
        <img src="/img/4.png" alt="">
        <span>心凉微软</span>
      </li>
      <li>
        <img src="/img/7.png" alt="">
        <span>哔哩哔哩</span>
      </li>
      <li>
        <img src="/img/8.png" alt="">
        <span>ACFUnds</span>
      </li>
      <li>
        <img src="/img/9.png" alt="">
        <span>plxiv</span>
      </li>
      <li>
        <img src="/img/10.png" alt="">
        <span>心凉微软</span>
      </li>
      
    </ul>
  </div>
</template>

<script>
  export default {
    name: 'SamllItem'
  }
</script>

<style scoped lang="stylus">
@import '../common/stylus/mixins.styl'
.small-item
  padding(15px)
  background rgba(247, 248, 243, .8)
  margin 20px 0


  .item-wrap
    display flex
    flex()
    padding(0)

    li
      display flex
      flex-direction column
      font-size 14px
      margin-left 20px
      margin-right 20px
      flex()
</style>