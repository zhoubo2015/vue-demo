<template>
  <div class="home">
    <h1>{{ msg}}</h1>
    <el-button-group>
        <el-button type="primary" icon="arrow-left">上一页</el-button>
        <el-button type="primary">下一页<i class="el-icon-arrow-right el-icon--right"></i></el-button>
    </el-button-group>
  </div>
</template>

<script>
export default {
  name: 'HomePage',
  data () {
    return {
      msg: 'Home'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
