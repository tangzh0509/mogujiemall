<template>
  <div id="app">
    <keep-alive exclude="Detail">
      <router-view></router-view>
    </keep-alive>
    <maintabbar/>
  </div>
</template>

<script>
import maintabbar from 'components/content/maintabbar/MainTabBar'
export default {
  name: 'app',
  components: {
    maintabbar
  }
}
</script>

<style>
  @import "assets/css/base.css";
</style>
