<template>
<el-row justify="center">
  <el-col :xs="24" :sm="18" :md="12" :lg="10">
   <app-post
        v-for="post in 3"
        :key="post"
      />
  </el-col>
</el-row>
</template>

<script>

import AppPost from '@/components/main/Post'
export default {

  components: {
    AppPost
  }
}
</script>

<style>
app-post{
  align-items: center;
}
</style>
