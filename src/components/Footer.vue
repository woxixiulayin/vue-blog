<template>
  <footer id='footer'>
    <div class="footer-info ">@{{ year }} <a href='#'>{{ author }}</a> Powered By <a :href='vueblogsite'>Vue-blog</a></div>
  </footer>
</template>

<script type="text/javascript">
import config from '../config'

export default {
  data: function () {
    return {
      year: new Date().getFullYear(),
      author: config.author
    }
  }
}
</script>

<style lang='scss'>
$fontcolor: blue;
$fontsize: 1rem;
$height: 3.5rem;
$bgcolor: rgb(217,237, 247);

#footer {
  text-align: center;
  background: $bgcolor;
}

#footer a {
  height: $height;
  line-height: $height;
  color: $fontcolor;
}
</style>  