<template>
      <el-result
        icon="warning"
        title="404提示"
        sub-title="页面不存在"
      >
        <template #extra>
          <el-button type="primary" @click="$router.push('/')">回到首页</el-button>
        </template>
      </el-result>
</template>

<script setup lang='ts'>
import { ref,reactive} from 'vue'
</script>

<style scoped lang='scss'>
</style>