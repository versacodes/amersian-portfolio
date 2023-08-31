<script setup>
import Cards from './components/Cards.vue'
import anime from 'animejs/lib/anime.es.js'
import { onMounted } from 'vue'

onMounted(() => {
  anime({
    targets: '.name',
    keyframes: [
      // reverse to start from 0 to 1 scale
      {scale: 1},
      {scale: 0},
    ],
    direction: 'reverse',
    // translateX: 0,
    duration: 1400
  })
})


</script>

<template>

  <header class="flex justify-between items-center bg-blue-950 py-4 px-6 md:px-10">
    <h1 class="text-lg md:text-xl font-bold text-yellow-50">versacodes</h1>
    <nav class="flex items-center justify-between">
      <a href="" class="md:mr-6 md:text-lg">Home</a>
      <a href="" class="md:text-lg">Projects</a>
    </nav>
  </header>

  <main class="bg-neutral-50 py-10 px-8 md:py-14 relative">
    <section class="md:w-[80%] mx-auto">
      <h1 class="text-xl md:text-2xl text-center text-zinc-700 mb-2">
        Hi, my name is<br>
        <span class="name scale-0 block text-zinc-900 mt-1 font-bold leading-8 text-3xl md:text-4xl mb-14">Franz Amersian Tiongson.</span>
      </h1>
      <p class="mt-4 text-center text-zinc-500 mx-auto text-[0.8rem] w-[12rem] md:w-full md:text-lg">
        I'm a
        <span class="underline font-bold text-zinc-600">Vue.js Front End Developer</span>
      </p>
      <div class="flex md:w-[80%] bg-zinc-500 text-white justify-between mx-auto py-2 px-4 mt-4 font-bold text-xs">
        <h4>HTML</h4>
        <h4>CSS</h4>
        <h4>Javascript</h4>
        <h4>Tailwind</h4>
        <h4>Vue</h4>
        <h4>Vue-Pinia</h4>
        <h4>Vue-Router</h4>
      </div>
      <button class="bg-orange-400 text-sm text-white font-bold p-3 mt-8 mx-auto block">My Projects</button>
    </section>
  </main>

  <section class="py-10">
    <Cards />
  </section>
  
  <section class="bg-neutral-50 py-10">
    <h1 class="text-center md:text-3xl text-2xl font-bold text-zinc-800">Contact Me</h1>
    <form class="px-4 py-2 mt-5 flex flex-col md:w-1/2 justify-center mx-auto">
        <input type="email"
               placeholder="Enter your email"
               class="p-3 mb-2 border-[1px] border-blue-950 border-solid"
               required>
        <textarea class="py-4 px-3 block resize-none w-[100%] h-[10rem] border-[1px] border-blue-950 border-solid"
                  placeholder="Enter your message"></textarea>
        <input class="mt-2 text-white py-3 px-4 bg-orange-400 font-bold"
               type="submit">
    </form>
  </section>

  <footer class="bg-blue-950 px-10 py-7">
    <p class="text-neutral-300 text-center text-xs md:text-sm">Created by Franz Amersian Tiongson</p>
  </footer>
</template>

<script>
</script>

<style scoped>

</style>
