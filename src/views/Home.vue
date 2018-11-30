<template>
  <div class="home">
    <Search />
    <Small-item />
    <Content />
  </div>
</template>

<script>
import Search from "./Search"
import SmallItem from "./SmallItem"
import Content from "./Content"

export default {
  name: 'home',
  components: {
    Search,
    SmallItem,
    Content
  }
}
</script>

<style lang="stylus" scoped>
.home
  width 1000px
  height 800px
  // background-color #456
</style>
