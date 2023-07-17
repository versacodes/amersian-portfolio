<script setup>

</script>

<template>

  <header class="flex justify-between items-center bg-blue-950 py-4 px-6">
    <h1 class="text-lg font-bold text-yellow-100">versacodes</h1>
    <nav class="w-[7rem] flex items-center justify-between">
      <a>Home</a>
      <a>Projects</a>
    </nav>
  </header>

  <main>
    <section class="py-10 px-8 bg-neutral-50">
      <h1 class="text-xl text-center text-zinc-700 mb-2">
        Hi, my name is<br>
        <span class="text-zinc-900 mt-1 inline-block font-bold leading-8 text-3xl">Franz Amersian.</span>
      </h1>
      <p class="mt-4 text-center text-zinc-700 mx-auto text-sm w-[12rem]">
        I'm a
        <span class="font-bold text-zinc-700">Vue.js Front End Developer</span>
      </p>
      <button class="bg-red-500 text-sm text-white font-bold p-3 mt-5 mx-auto block">My Projects</button>
    </section>
  </main>

  <section class="py-9">
    <h1 class="text-2xl font-bold text-center mb-2 text-zinc-900">My Projects</h1>
    <div>
        <!-- the div below should loop over my projects later -->
        <div class="hover:scale-[1.03] py-4 px-6 flex flex-col justify-center items-center">
            <!-- just temporary image for now -->
            <img src="./assets/plant4.jpg"
                 alt="Project"
                 class="h-[16rem] w-[100%]">
            <div class="text-center bg-blue-950 p-6">
                <h1 class="text-xl text-white font-semibold mb-4">Ecommerce Store</h1>
                <p class="text-sm text-neutral-100 leading-6">Integer ultricies malesuada quam. Duis ac nulla varius diam ultrices rutrum.</p>
            </div>
        </div>
    </div>
  </section>
  
  <section class="bg-neutral-50 py-9">
    <h1 class="text-center text-2xl font-bold text-zinc-800">Contact Me</h1>
    <form class="px-4 py-2 mt-5">
        <input type="email"
               placeholder="Enter your email"
               class="p-3 mb-2"
               required>
        <textarea class="py-4 px-3 resize-none w-[100%] h-[10rem]"
                  placeholder="Enter your message"></textarea>
        <input class="mt-2 py-3 px-4 bg-orange-400 font-bold"
               type="submit">
    </form>
  </section>
</template>

<style scoped>

</style>
