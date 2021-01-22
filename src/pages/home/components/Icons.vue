<template>
  <div class="icons">
    <div class="block"
    v-for="item in urls"
    :key="item.url">
      <el-image
        style="width: 50px; height: 50px"
        :src="item.url"
        fit="fit">
      </el-image>
       <span class="name">{{item.name}}</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
  data () {
    return {
      urls: [
        {
          url: 'https://s.qunarzz.com/homenode/images/touchheader/hotel.png',
          name: '酒店'
        },
        {
          url: 'https://s.qunarzz.com/homenode/images/touchheader/flight.png',
          name: '机票'
        },
        {
          url: 'https://s.qunarzz.com/homenode/images/touchheader/train.png',
          name: '火车票'
        },
        {
          url: 'https://s.qunarzz.com/homenode/images/touchheader/package.png',
          name: '度假'
        },
        {
          url: 'https://s.qunarzz.com/homenode/images/touchheader/piao.png',
          name: '景点门票'
        },
        {
          url: 'https://picbed.qunarzz.com/f5e5770393d759578962e53ee67798c8.png',
          name: '海外酒店'
        },
        {
          url: 'https://picbed.qunarzz.com/a36d2288f19e54562338f4d8ef986288.png',
          name: '低价机票'
        },
        {
          url: 'https://picbed.qunarzz.com/377db8cb2143aebf01869c9baad3d325.png',
          name: '汽车票船票'
        },
        {
          url: 'https://picbed.qunarzz.com/ae617a31e0bd5803d76918b817f6d942.png',
          name: '自由行'
        },
        {
          url: 'https://picbed.qunarzz.com/1316dc82d1ce6259686d5a68880e5a9d.png',
          name: '攻略'
        }
      ]
    }
  }
}
</script>

<style scoped>
.icons {
  height: 0;
  background-color: green;
  display: flex;
  flex-wrap: wrap;
}
.block {
  width: 75px;
  height: 75px;
}
.name {
  display: block;
  font-size: .1rem;
  width: 75px;
  height: 75px;
}
</style>
