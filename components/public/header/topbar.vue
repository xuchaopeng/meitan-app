<template>
  <el-row :gutter="15">
    <el-col :span="4">
       <Geo />
    </el-col>
    <el-col :span="6">
      <User />
    </el-col>
    <el-col :span="14">
      <Navbar />
    </el-col>
  </el-row>
</template>

<script>
import Geo from './geo.vue';
import User from './user.vue';
import Navbar from './nav';
export default {
  components:{
    Geo,
    User,
    Navbar
  }
}
</script>

<style lang="scss">

</style>
