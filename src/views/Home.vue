<template>
  <div class="home-search-panel">
    <MySearchLogo class="my-search-logo"></MySearchLogo>
    <SimpleSearchBar class="search-bar"/>
  </div>
</template>

<script>

import MySearchLogo from '@/components/MySearchLogo.vue'
import SimpleSearchBar from '@/components/SimpleSearchBar.vue'

export default {
  name: 'home',
  components: {
    MySearchLogo,
    SimpleSearchBar
  }
}
</script>


<style lang="less" scoped>
.home-search-panel{
  min-width:840px;
}
.my-search-logo{
  margin-top: 60px;
  margin-bottom: 30px;
}
.search-bar{
  margin: 0 auto;
}
</style>
