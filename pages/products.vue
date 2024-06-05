<template>
  <div>
    <main class="container mx-auto py-8">
      <section class="bg-white dark:bg-gray-900">
        <div class="h-[32rem] bg-gray-100 dark:bg-gray-800">
          <div class="container px-6 py-10 mx-auto">
            <h1 class="text-2xl font-semibold text-center text-gray-800 capitalize lg:text-3xl dark:text-white">Products</h1>

            <div class="flex justify-center mx-auto mt-6">
              <span class="inline-block w-40 h-1 bg-customRed rounded-full"></span>
              <span class="inline-block w-3 h-1 mx-1 bg-customRed rounded-full"></span>
              <span class="inline-block w-1 h-1 bg-customRed rounded-full"></span>
            </div>

            <p class="max-w-2xl mx-auto mt-6 text-center text-gray-500 dark:text-gray-300">
              We've launched three exclusive agency products in Indonesia: One Piece series, Sanrio series, and Pokémon series.
            </p>
            <p class="max-w-2xl mx-auto mt-6 text-center text-gray-500 dark:text-gray-300">
              Each of our products comes with different reward positions, making your card collecting hobby not only more fun but also more profitable.
            </p>
            <p class="max-w-2xl mx-auto mt-6 text-center text-gray-500 dark:text-gray-300">
              In the fourth quarter of 2024, Donji will launch the Card game of Southeast Asia's top IP, Mobile Legends,
              and conduct public testing of online blind box machines and live streaming platforms. Stay tuned for updates.
            </p>
          </div>
        </div>

        <div class="container px-6 py-10 mx-auto -mt-72 sm:-mt-80 md:-mt-96">
          <div class="grid grid-cols-1 gap-8 mt-8 xl:mt-16 md:grid-cols-2 xl:grid-cols-3">
            <div class="flex flex-col items-center p-4 border sm:p-6 rounded-xl dark:border-gray-700">
              <img class="object-cover w-full rounded-xl aspect-square"
                   src="https://images.unsplash.com/photo-1535713875002-d1d0cf377fde?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=880&q=80"
                   alt="">

            </div>

            <div class="flex flex-col items-center p-4 border sm:p-6 rounded-xl dark:border-gray-700">
              <img class="object-cover w-full rounded-xl aspect-square"
                   src="https://images.unsplash.com/photo-1531590878845-12627191e687?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=764&q=80"
                   alt="">

            </div>

            <div class="flex flex-col items-center p-4 border sm:p-6 rounded-xl dark:border-gray-700">
              <img class="object-cover w-full rounded-xl aspect-square"
                   src="https://images.unsplash.com/photo-1570295999919-56ceb5ecca61?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=880&q=80"
                   alt="">

            </div>
          </div>
        </div>
      </section>
    </main>
  </div>
</template>

<script setup>
import Navbar from "@/components/Navbar.vue";
</script>
