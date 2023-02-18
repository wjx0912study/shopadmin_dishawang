<script setup>
</script>

<template>
    <button class="btn">按钮</button>
    <!-- <el-row class="mb-4">
      <el-button>Default</el-button>
      <el-button type="primary">Primary</el-button>
      <el-button type="success">Success</el-button>
      <el-button type="info">Info</el-button>
      <el-button type="warning">Warning</el-button>
      <el-button type="danger">Danger</el-button>
    </el-row> -->
    <router-view></router-view>
</template>

<style scoped>
.btn {
    @apply  bg-purple-500 text-indigo-50 px-4 py-2 rounded-full
     hover:(bg-purple-900) transition-all duration-500
     focus:(ring-2 ring-purple-400);
}
</style>
