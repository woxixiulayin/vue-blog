<template>
  <footer id='footer'>
    <div class="footer-info ">@{{ year }} <a href='#'>{{ author }}</a> Powered By <a :href='vueblogsite' target='_blank'>Vue-blog</a></div>
  </footer>
</template>

<script type="text/javascript">
import config from '../config'

export default {
  data: function () {
    return {
      year: new Date().getFullYear(),
      author: config.author,
      vueblogsite: 'https://github.com/woxixiulayin/vue-blog'
    }
  }
}
</script>

<style lang='scss'>
$linkcolor: rgb(37, 143, 184);
$fontsize: 1rem;
$height: 3.5rem;
$bgcolor: rgb(38, 42, 48);

#footer {
  text-align: center;
  background: $bgcolor;
  color: #ccc;
}

#footer a {
  height: $height;
  line-height: $height;
  color: $linkcolor;
}
</style>  