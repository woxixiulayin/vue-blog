<template>
  <header>
    <h1>{{ siteTitle }}</h1>
  </header>
</template>

<script>
import config from '../config'

export default {
  data: function () {
    return {
      siteTitle: config.siteTitle || 'Vue-blog'
    }
  }
}

</script>

<style lang='scss'>
$bgcolor: rgb(0,127,195);
$fontcolor: white;
$fontsize: 3.5rem;
$height: 8rem;

header {
  width: 100%;
  height: $height;
  background-color: $bgcolor;
}

h1 {
  text-align: center;
  line-height: $height;
  font-size: $fontsize;
  color: $fontcolor;
}

</style>