<template>
  <div>
    <h3>user list</h3>
    <post-item v-for="post in posts" :post="post" />
  </div>
</template>

<script>
import PostItem from './PostItem.vue';

export default {
  props: {
    posts: {
      type: Object,
      requrired: true,
    },
  },
  components: { PostItem },
};
</script>

<style></style>
