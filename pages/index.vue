<template>
  <div align="center" class="root">
    <div>
      <span class="GodoB" style="font-size: 3em;">전체 글</span>
      <post-list />
    </div>
  </div>

</template>

<script>
  import PostList from "../components/PostList";
  export default {
    components: {PostList},
    middleware: 'allPosts'

  }
</script>

<style lang="scss" scoped>
</style>
