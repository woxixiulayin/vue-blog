<template>
  <article class='main-body'>
    <component :is="currentView"></component>
  </article>
  <side></side>
</template>

<script type="text/javascript">
import postslist from './Postslist.vue'
import post from './Post.vue'
import side from './Aside.vue'

export default {
  data: {
    currentView: postslist
  },
  components: {
    postslist,
    post,
    side
  }
}

</script>

<style lang='scss'>

.main-body{
  position: relative;
  width: 100%;
  background: #eee;
  min-height: 1000px;
}

</style>