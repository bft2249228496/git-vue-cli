<template>
  <div class="recommend">
    <div class="recommend-title">
      {{ msg }}
    </div>
    <ul>
      <li>
        <div class="item">
          <img src="" alt="" class="item-img" />
          <div class="item-info">
          <p class="item-title">大连圣亚海洋世界</p>
          <p class="item-desc">浪漫大连首站，浪漫的海洋主题乐园</p>
          <button class="item-button">查看详情</button>
        </div>
        </div>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Header',
  data () {
    return {
      msg: '热销推荐'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.recommend-title {
  margin-top: 3rem;
  line-height: 0.8rem;
  background: #eee;
  text-indent: 0.2rem;
  font-size: .3rem;
  text-align: left;
}
.item {
  height: 2.4rem;
  display: flex;
  overflow: hidden;
  background-color: #f00;
  width: 100%;
}
.item-img {
  width: 2.2rem;
  height: 2.2rem;
  padding: .1rem;
}
.item-info {
  flex: 1;
  padding: .1rem;
}
.item-title {
  font-size: .4rem;
  height: .4rem;
}
.item-desc {
  font-size: .36rem;
  margin-top: .2rem;
  color: #ccc;
  height: .7rem;
}
.item-button {
  margin-top: 0;
  margin-left: -3.6rem;
  background: #ff9300;
  padding: 0 .2rem;
  border-radius: .06rem;
  color: #fff;
  font-size: .3rem;
}
</style>
