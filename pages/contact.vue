<template>
  <div>
    <main class="container mx-auto py-8 h-screen">
      <section class="bg-white dark:bg-white">
        <div class="container px-6 py-12 mx-auto">
          <h1 class="text-3xl font-semibold text-center text-customRed capitalize lg:text-8xl dark:text-customRed">Cooperation/JoinUs</h1>
          <div class="flex justify-center mx-auto mt-6">
            <span class="inline-block w-40 h-1 bg-customRed rounded-full"></span>
            <span class="inline-block w-3 h-1 mx-1 bg-customRed rounded-full"></span>
            <span class="inline-block w-1 h-1 bg-customRed rounded-full"></span>
          </div>

          <!--Coopertaion-->
          <div class="text-center py-10">

            <h1 class="mt-2 text-2xl font-semibold text-gray-800 md:text-6xl dark:text-customRed">Cooperation</h1>

          </div>

          <div class="grid grid-cols-1 gap-12 mt-10 md:grid-cols-2 lg:grid-cols-2">
            <div class="flex flex-col items-center justify-center text-center">

              <h2 class="mt-4 text-xl lg:text-5xl font-semibold text-gray-800 dark:text-black">Noah Zhang</h2>
              <a href="mailto:noahzzz0214@gmial.com"
                 class="mt-2 text-lg font-semibold lg:text-2xl text-red-500 dark:text-red-400">noahzzz0214@gmail.com
              </a>
            </div>

            <div class="flex flex-col items-center justify-center text-center">

              <h2 class="mt-4 text-xl lg:text-5xl font-semibold text-gray-800 dark:text-black">Frank Choo</h2>
              <a href="mailto:frankchoo3200@gmail.com"
                 class="mt-2 text-lg font-semibold lg:text-2xl text-red-500 dark:text-red-400">frankchoo3200@gmail.com
              </a>
            </div>

          </div>

          <!--JoinUs-->
          <div class="text-center py-10">

            <h1 class="mt-2 text-2xl font-semibold text-gray-800 md:text-6xl dark:text-customRed">Join Us</h1>

          </div>

          <div class="grid grid-cols-1 gap-12 mt-10 md:grid-cols-2 lg:grid-cols-1">
            <div class="flex flex-col items-center justify-center text-center">

              <h2 class="mt-4 text-xl lg:text-5xl font-semibold text-gray-800 dark:text-black">Dikdik Fauzi Sidqi S.S, CHRP</h2>
              <p class="mt-4 text-base lg:text-3xl font-semibold text-gray-800 dark:text-black">HR & GA Director</p>
              <p class="mt-2 text-base font-semibold lg:text-2xl text-black-200 dark:text-black-400">+62 813-1113-3000
              </p>
              <a href="mailto:hr.eastcollectionindonesia@gmail.com"
                 class="mt-2 text-lg font-semibold lg:text-2xl text-red-500 dark:text-red-400">hr.eastcollectionindonesia@gmail.com
              </a>
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
