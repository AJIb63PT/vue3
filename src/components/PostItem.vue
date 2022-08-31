<template>
  <div class="post">
    <div><strong>title</strong>{{ post.title }}</div>
    <div><strong>body</strong>{{ post.body }}</div>
  </div>
</template>

<script>
export default {
  props: {
    post: {
      type: Object,
      requrired: true,
    },
  },
};
</script>

<style>
.post {
  padding: 15px;
  border: 2px solid teal;
  margin-top: 15px;
}
</style>
