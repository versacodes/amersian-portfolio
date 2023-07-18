<script setup>

</script>

<template>

  <header class="flex justify-between items-center bg-blue-950 py-4 px-6 md:px-10">
    <h1 class="text-lg md:text-xl font-bold text-yellow-50">versacodes</h1>
    <nav class="flex items-center justify-between">
      <a href="" class="md:mr-5 md:text-lg">Home</a>
      <a href="" class="md:text-lg">Projects</a>
    </nav>
  </header>

  <main class="bg-neutral-50 py-10 px-8 md:py-14">
    <section class="md:w-[80%] mx-auto">
      <h1 class="text-xl md:text-2xl text-center text-zinc-700 mb-2">
        Hi, my name is<br>
        <span class="text-zinc-900 mt-1 inline-block font-bold leading-8 text-3xl md:text-4xl">Franz Amersian Tiongson.</span>
      </h1>
      <p class="mt-4 text-center text-zinc-700 mx-auto text-[0.8rem] w-[12rem] md:w-full md:text-lg">
        I'm a
        <span class="underline font-bold text-zinc-700">Vue.js Front End Developer</span>
      </p>
      <button class="bg-orange-400 text-sm text-white font-bold p-3 mt-8 mx-auto block">My Projects</button>
    </section>
  </main>

  <section class="py-9">
    <h1 class="text-2xl font-bold text-center mb-2 text-zinc-900">My Projects</h1>
    <div>
        <!-- the div below should loop over my projects later -->
        <div class="hover:scale-[1.03] py-4 px-6 flex flex-col justify-center items-center md:w-[50%] mx-auto">
            <!-- just temporary image for now -->
            <img src="./assets/plant4.jpg"
                 alt="Project"
                 class="h-[16rem] w-[100%]">
            <div class="text-center bg-blue-950 p-6">
                <h1 class="text-xl text-white font-semibold mb-4">Ecommerce Store</h1>
                <p class="text-sm text-neutral-100 leading-6">Integer ultricies malesuada quam. Duis ac nulla varius diam ultrices rutrum.</p>
            </div>
                <button class="bg-orange-400 p-3 w-full text-white font-bold">Go to Website</button>
        </div>
    </div>
  </section>
  
  <section class="bg-neutral-50 py-9">
    <h1 class="text-center text-2xl font-bold text-zinc-800">Contact Me</h1>
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

<style scoped>

</style>
