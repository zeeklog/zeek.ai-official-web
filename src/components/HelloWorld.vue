<template>
  <div class="m-full h-[100vh] overflow-hidden rounded-md relative">
    <Vortex
      background-color="black"
      class="flex size-full flex-col items-center justify-center px-2 py-4 md:px-10"
    >
      <h2 class="text-center text-2xl font-bold text-white md:text-6xl">极客.ai</h2>
      <p class="mt-6 max-w-xl text-center text-sm text-white md:text-2xl">
        一款专为前沿科技爱好者打造的桌面软件，集成市面上主流的AI聊天、AI绘画、AI视频生成等ai产品。内置100+款极客日常必备工具，助你高效工作与创作。结合无障碍全球AI实时搜索，极客AI让你轻松驾驭智能时代，探索无限可能。
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
