<template>
  <nav class="global-nav">
    <ul class='menu'>
      <li class='menu-item'><a href='#'>首页</a></li>
      <li class='menu-item'><a href='#'>关于</a></li>
    </ul>
  </nav>
</template>

<script>
  export default { }
</script>

<style lang='scss'>
$bgcolor: rgb(49,49,49);
$fontcolor: white;
$hovercolor: rgb(228,22,53);
$fontsize: 1.2rem;
$height: 2.5rem;
$bodywidth: 50rem;

.global-nav {
  width: 100%;
  background-color: $bgcolor;
}

.menu {
  background: transparent;
  width: $bodywidth;
  margin: 0 auto;
  overflow: hidden;
}

.menu-item {
  float: left;
  height: $height;
  line-height: $height;
  font-size: $fontsize;
  color: $fontcolor;
  padding:0 1.5rem;
  transition: all 1s;
  font-family: "Microsoft Yahei", Arial, Helvetica, sans-serif;
}

.menu-item:hover {
  background-color: $hovercolor;
}

</style>