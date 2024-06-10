<template>
  <div>
    <main class="container mx-auto py-8 h-screen">
      <section class="bg-white dark:bg-white">
        <div class="h-[32rem] bg-gray-100 dark:bg-white">
          <div class="container px-6 py-10 mx-auto">
            <h1 class="text-2xl font-semibold text-center text-customRed capitalize lg:text-8xl dark:text-customRed">Products</h1>

            <div class="flex justify-center mx-auto mt-6">
              <span class="inline-block w-40 h-1 bg-customRed rounded-full"></span>
              <span class="inline-block w-3 h-1 mx-1 bg-customRed rounded-full"></span>
              <span class="inline-block w-1 h-1 bg-customRed rounded-full"></span>
            </div>

            <p class="max-w-2xl mx-auto mt-6 text-justify text-gray-500 text-xl font-semibold dark:text-black">
              We've launched three exclusive agency products in Indonesia: One Piece series, Sanrio series, and Pokémon series.<br>
              Each of our products comes with different reward positions, making your card collecting hobby not only more fun but also more profitable.<br>
              In the fourth quarter of 2024, Donji will launch the Card game of Southeast Asia's top IP, Mobile Legends,
              and conduct public testing of online blind box machines and live streaming platforms. Stay tuned for updates.
            </p>

          </div>
        </div>

        <div class="container px-6 py-64 mx-auto -mt-72 sm:-mt-80 md:-mt-96">
          <div class="grid grid-cols-1 gap-8 mt-8 xl:mt-16 md:grid-cols-2 xl:grid-cols-3">
            <div class="flex flex-col items-center p-4  sm:p-6 rounded-xl dark:border-gray-700">
              <img class="object-cover w-full rounded-xl aspect-square"
                   src="/img/card1.png"
                   alt="">

            </div>

            <div class="flex flex-col items-center p-4  sm:p-6 rounded-xl dark:border-gray-700">
              <img class="object-cover w-full rounded-xl aspect-square"
                   src="/img/card2.png"
                   alt="">

            </div>

            <div class="flex flex-col items-center p-4  sm:p-6 rounded-xl dark:border-gray-700">
              <img class="object-cover w-full rounded-xl aspect-square"
                   src="/img/card3.png"
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
