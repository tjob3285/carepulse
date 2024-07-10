<template>
  <NuxtLayout :name="layout">
    <NuxtPage />
  </NuxtLayout>
</template>

<script setup lang="ts">
// Supports weights 200-800
import '@fontsource-variable/plus-jakarta-sans';

const layout = "custom"

useSeoMeta({
  title: 'CarePulse',
  ogTitle: 'CarePulse',
  description: 'A healthcare management system.',
  ogDescription: 'A healthcare management system.',
})
</script>

<style>
body {
  font-family: 'Plus Jakarta Sans Variable', sans-serif;
}
</style>