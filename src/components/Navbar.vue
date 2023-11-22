<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>

<template>
  <nav>
    <RouterLink to="/">Blog</RouterLink>
    <RouterLink to="/about">Sobre</RouterLink>
    <RouterLink to="/description">Descrição</RouterLink>
  </nav>
</template>

<style scoped>
nav {
  display: flex;
  justify-content: center;
  gap: 16px;
  padding-top: 16px;
}
</style>
