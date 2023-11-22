<script setup lang="ts">
import BlogPostDescription from './BlogPostDescription.vue'
import postJson from '@/api/posts.json'
</script>
<template>
  <main>
    <h1>Últimas do blog</h1>

    <BlogPostDescription
      v-for="post in postJson.posts"
      :title="post.title"
      :description="post.body"
    />

    <button>Ver mais</button>
  </main>
</template>

<style scoped>
main {
  display: flex;
  flex-direction: column;
  align-self: center;

  width: 50vw;
}

h1 {
  padding: 16px;
  align-self: center;
}

button {
  background: none;
  border: none;
  font-weight: bold;
  color: royalblue;
  cursor: pointer;
  padding: 16px;
}

button:hover {
  font-size: medium;
}
</style>
