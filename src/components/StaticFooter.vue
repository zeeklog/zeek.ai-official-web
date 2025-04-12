<script setup lang="ts">
// useStore and computed are automatically imported. See vite.config.ts for details.
const store = useStore()
defineProps<{
  msg: string
  optionalProp?: number
}>()

function increment() {
  store.increment()
}
</script>

<template>
  <h2>{{ msg }}</h2>
</template>
