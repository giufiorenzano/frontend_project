<script setup lang="ts">
defineProps<{
  title?: string
  description?: string
}>()
</script>

<template>
  <h3>{{ title }}</h3>
  <p>{{ description }}</p>
</template>

<style scoped>
h3 {
  font-weight: bold;
}

p {
  font-style: italic;
  margin-bottom: 16px;
  text-align: justify;
}
</style>
