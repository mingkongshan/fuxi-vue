<template>
  <!-- 放置一个外层容器 -->
  <el-container>
    <!-- 左右布局 -->
    <el-aside style="background-color:#353b4e;height:100vh;width:230px">
      <!-- 放置一个左侧组件 -->
      <layout-aside></layout-aside>
    </el-aside>
    <!-- 再放置一个container -->
    <el-container>
      <!-- 上下布局 -->
      <el-header>
        头部
      </el-header>
      <!-- 主要区域 -->
      <el-main>
        主要区域
      </el-main>
    </el-container>
  </el-container>
</template>

<script>
import layoutAside from '../../components/home/layout-aside' // 引入
export default {
  components: {
    'layout-aside': layoutAside
  }
}
</script>

<style>

</style>
