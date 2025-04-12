<script setup lang="ts">
// See vite.config.ts for details about automatic imports
const route = useRoute()

useHead({
  title: () => route.meta.title || 'Vite tailwindCss starter',
  meta: [
    {
      property: 'og:title',
      content: () => route.meta.title,
    },
  ],
})
</script>
<template>
  <router-view />
</template>
