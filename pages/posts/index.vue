<template>
  <div class="post-page">
    <PostList></PostList>
  </div>
</template>

<script>
import PostList from '@/components/Posts/PostList.vue'
export default {
  components: {
    PostList
  }
}
</script>

<style scoped>
.post-page {
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
