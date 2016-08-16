<template>
  <div class='main-body'> 
  <div class='content'>
  <router-view
    transition
    transition-mode="out-in">
  </router-view>
  </div>
  <side></side>
  </div>
</template>

<script type="text/javascript">
import postslist from './Postslist.vue'
import post from './Post.vue'
import side from './Aside.vue'

export default {
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