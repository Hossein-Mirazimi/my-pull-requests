<script setup>
useHead({
  htmlAttrs: {
    lang: 'en',
  },
})
</script>

<template>
  <NuxtPage />
  <ScrollToTop />
</template>

<style lang="postcss">
body {
  @apply min-h-screen bg-white dark:bg-gray-900 text-gray-700 dark:text-gray-200 font-sans;
}
</style>
