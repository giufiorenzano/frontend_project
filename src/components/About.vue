<script setup lang="ts">
import Navbar from '@/components/Navbar.vue'
import Profile from './Profile.vue'
</script>

<template>
  <header>
    <Navbar />

    <Profile />
  </header>
</template>

<style scoped>
header {
  background-color: #63adf2;
  padding: 16px;
}
</style>
