<template>
  <div id="app" class="pure-g">
    <div class="pure-u-1 pure-u-md-1-4"><img class="logo" src="./assets/botijo.gif"></div>
    <div class="pure-u-1 pure-u-md-3-4"><h1>{{ msg }}</h1></div>
    <div class="pure-u-1 pure-u-md-1-2 pure-u-lg-1-4">A</div>
    <div class="pure-u-1 pure-u-md-1-2 pure-u-lg-1-4">B</div>
    <div class="pure-u-1 pure-u-md-1-2 pure-u-lg-1-4">C</div>
    <div class="pure-u-1 pure-u-md-1-2 pure-u-lg-1-4">D</div>
    <div class="pure-u-1">FOOTER</div>

  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Vue.js + Pure.css bundled with Webpack'
    }
  }
}
</script>

<style>
.logo {
  width: 50px;
}
</style>
