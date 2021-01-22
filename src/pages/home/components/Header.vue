<template>
  <div class="header">
   <div class="header-left">
     <span class="iconfont">&#xe624;</span>
   </div>
   <div class="header-input">
     <span class="iconfont">&#xe632;</span>
     内容
   </div>
   <div class="header-right">
     {{city}}
     <span class="iconfont iconfont-city">&#xe64a;</span>
   </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
  props: ['city'],
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .block {
    display: block;
  }
  .header {
    display: flex;
    line-height: .86rem;
    align-items: center;
    background-color: #00bcd4;
    color: #fff;
    font-size: 0.4rem;
  }
  .header-left {
    text-align: center;
  }
  .header-input {
    flex: 1;
    text-align: center;
    background-color: #fff;
    border-radius: .1rem;
    margin-top: .12rem;
    margin-bottom: .12rem;
    color: #ccc;
    display: flex;
    padding-left: .2rem;
  }
  .header-right {
    text-align: center;
    display: flex;
  }
  .iconfont {
    font-size: .4rem;
    display: block;
  }
  .iconfont-city {
   font-size: .2rem;
  }
</style>
