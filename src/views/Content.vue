<template>
  <section class="content">
    <ul class="content-wrap">
      <li class="index">常用网站</li>
      <li>谷歌日本</li>
      <li>谷歌邮箱</li>
      <li>Youtube</li>
      <li>天气预报</li>
      <li>华尔街新闻</li>
      <li>待添加</li>
      <li>电视直播</li>
    </ul>
    <ul class="content-wrap">
      <li class="index">常用网站</li>
      <li>谷歌日本</li>
      <li>谷歌邮箱</li>
      <li>Youtube</li>
      <li>天气预报</li>
      <li>华尔街新闻</li>
      <li>待添加</li>
      <li>电视直播</li>
    </ul>
    <ul class="content-wrap">
      <li class="index">常用网站</li>
      <li>谷歌日本</li>
      <li>谷歌邮箱</li>
      <li>Youtube</li>
      <li>天气预报</li>
      <li>华尔街新闻</li>
      <li>待添加</li>
      <li>电视直播</li>
    </ul>
    <ul class="content-wrap">
      <li class="index">常用网站</li>
      <li>谷歌日本</li>
      <li>谷歌邮箱</li>
      <li>Youtube</li>
      <li>天气预报</li>
      <li>华尔街新闻</li>
      <li>待添加</li>
      <li>电视直播</li>
    </ul>
  </section>
</template>

<script>
  export default {
    name: 'Content'
  }
</script>

<style lang="stylus" scoped>
@import '../common/stylus/mixins.styl'
@import '../common/stylus/variable.styl'

.content
  background-color rgba(255, 253, 246, .8)
  padding(5px)

  .content-wrap
    display flex
    flex()
    justify-content flex-start
    padding(5px)

    li
      margin-right 30px
      padding(5px)
      font-size 14px

    li.index
      background-color #ffc94e
      color #ffffff
      bdRadius(5px)
</style>