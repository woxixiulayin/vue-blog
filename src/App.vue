<template>
  <app-header></app-header>
  <app-nav></app-nav>
  <app-body></app-body>
  <app-footer></app-footer>
</template>

<script>
import appHeader from './components/Header.vue'
import appNav from './components/Nav.vue'
import appBody from './components/Body.vue'
import appFooter from './components/Footer.vue'

export default {
  components: {
    appHeader,
    appNav,
    appBody,
    appFooter
  }
}
</script>

<style>
/*重置样式*/
body, html, div, blockquote, img, label, p, h1, h2, h3, h4, h5, h6, pre, ul, ol,
li, dl, dt, dd, form, a, fieldset, input, th, td
{margin: 0; padding: 0; border: 0; outline: none;}
ul, ol{list-style: none;}
a{color: black;text-decoration: none;}
a:hover
{text-decoration: underline;}

</style>
