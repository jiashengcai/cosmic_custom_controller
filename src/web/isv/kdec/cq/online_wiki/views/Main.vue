<template>
  <div class="customright">
    <OnlineWiki class="child-view"></OnlineWiki>
  </div>
</template>
<script>
import OnlineWiki from "./OnlineWiki.vue";
export default {
  name: 'Main',
  components: {
    OnlineWiki
  }
}
</script>
<style>
@import "https://unpkg.com/element-ui/lib/theme-chalk/index.css";
</style>
