<template>
  <el-carousel indicator-position="inside" style="height:114px">
    <el-carousel-item v-for="item in dataList" :key="item">
      <h3>
        <el-image
        style="width: 100%; height: auto"
        :src="item"
        fit="fit">
        </el-image>
      </h3>
    </el-carousel-item>
  </el-carousel>
</template>

<script>

export default {
  name: 'HomeSwiper',
  data () {
    return {
      dataList: [
        'https://imgs.qunarzz.com/vs_ceph_vcimg/f03f5ac90ae59d0d9c6332a2bfd9782e.jpeg',
        'https://imgs.qunarzz.com/vs_ceph_vcimg/f7813c9431796cc32ae7b7a78447342e.jpeg',
        'https://imgs.qunarzz.com/vs_ceph_vcimg/569cae4ae98e9793f7341e85eed73c54.jpeg'
      ]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .el-carousel__item h3 {
    color: #475669;
    font-size: 18px;
    opacity: 0.75;
    line-height: 300px;
    margin: 0;
  }
  .el-carousel__item:nth-child(2n) {
    background-color: #99a9bf;
  }
  .el-carousel__item:nth-child(2n+1) {
    background-color: #d3dce6;
  }
  /deep/ .el-carousel__button {
    width: 10px;
    height: 10px;
    border-radius: 100%;
  }
</style>
