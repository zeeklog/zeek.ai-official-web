<template>
  <div class="m-full h-[100vh] overflow-hidden rounded-md relative">
    <Vortex
      background-color="black"
      class="flex size-full flex-col items-center justify-center px-2 py-4 md:px-10"
    >
      <h2 class="text-center text-2xl font-bold text-white md:text-6xl">Vite Typescript Shadcn-vue Tailwindcss Starter</h2>
      <p class="mt-6 max-w-xl text-center text-sm text-white md:text-2xl">
        A Vite project quick starter with : Typescript, Shadcn-vue, Tailwindcss@4, Vue-Router@4 and vue components auto import.
      </p>
      <div class="mt-6 flex flex-col items-center gap-4 sm:flex-row cursor-pointer">
        <GradientButton bg-color="#fff" @click="open('https://github.com/zeeklog/zeek.ai/releases')">🖥️ Windows版下载</GradientButton>
        <GradientButton bg-color="#fff"  @click="open('https://github.com/zeeklog/zeek.ai/releases')">💻 MAC版下载</GradientButton>
      </div>
    </Vortex>
  </div>
</template>

<script lang="ts" setup>
const open = (url: string) => {
  window.open(url)
}
</script>
