<script setup lang="ts">
// See vite.config.ts for details about automatic imports
import StaticFooter from '@/components/StaticFooter.vue'
import MainHeader from '@/components/MainHeader.vue'

</script>
<template>
  <header>
   <main-header msg=""></main-header>
  </header>
  <main>
    <HelloWorld />
  </main>
  <footer>
    <static-footer msg="" />
  </footer>
</template>
