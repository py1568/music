<template>
  <div id="app">
    <mHeader></mHeader>
    <tab></tab>
    <keep-alive>
      <router-view></router-view>
    </keep-alive>
  </div>
</template>

<script>
import mHeader from '@/components/m-header/m-header'
import Tab from '@/components/tab/tab'

export default {
  name: 'App',
  components: {
    mHeader,
    Tab
  }
}
</script>

<style scoped lang="stylus">
  @import "~common/stylus/variable";

  #app
    color: $color-theme
</style>
