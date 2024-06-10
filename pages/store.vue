<template>
  <div>
    <main class="container mx-auto py-8 h-screen">
      <div class="container px-6 py-10 mx-auto">
        <h1 class="text-2xl font-semibold text-center text-customRed capitalize lg:text-8xl dark:text-customRed">Online Store</h1>

        <div class="flex justify-center mx-auto mt-6">
          <span class="inline-block w-40 h-1 bg-customRed rounded-full"></span>
          <span class="inline-block w-3 h-1 mx-1 bg-customRed rounded-full"></span>
          <span class="inline-block w-1 h-1 bg-customRed rounded-full"></span>
        </div>

        <div class="grid grid-cols-1 gap-8 mt-8 xl:mt-12 xl:gap-12 md:grid-cols-2 xl:grid-cols-3">
          <div>
            <img class="object-cover w-full rounded-lg h-96 "
                 src="/img/eastcostore.png"
                 alt="Eastco Store">
          </div>

          <div>
            <img class="object-cover w-full rounded-lg h-96 "
                 src="/img/tiktok.png"
                 alt="TikTok">
          </div>

          <div>
            <img class="object-cover w-full rounded-lg h-96 "
                 src="/img/ins.png"
                 alt="Ins">
          </div>
        </div>
      </div>
    </main>
  </div>
</template>

<script setup>
import Navbar from "@/components/Navbar.vue";
</script>
