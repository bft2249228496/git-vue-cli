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
      msg: '周末去哪儿'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.recommend-title {
  line-height: 0.8rem;
  background: #eee;
  text-indent: 0.2rem;
  font-size: 0.3rem;
  text-align: left;
}
.item {
  height: 3rem;
  overflow: hidden;
  background-color: #f00;
  width: 100%;
}
.item-img {
  width: 100%;
  height: 1.4rem;
  padding: 0.1rem;
}
.item-info {
  padding: 0.1rem;
}
.item-title {
  font-size: 0.4rem;
  height: 0.4rem;
}
.item-desc {
  font-size: 0.36rem;
  margin-top: 0.2rem;
  color: #ccc;
  height: 0.7rem;
}
.item-button {
  margin-top: 0;
  margin-left: -3.6rem;
  background: #ff9300;
  padding: 0 0.2rem;
  border-radius: 0.06rem;
  color: #fff;
  font-size: 0.3rem;
}
</style>
