<template>
  <header>
    <nav class="bg-white shadow dark:bg-customRed">
      <div class="container flex items-center justify-center p-6 mx-auto text-gray-600 capitalize dark:text-gray-300">
        <a :class="[
            isActive('/')
              ? 'text-gray-800 transition-colors duration-300 transform dark:text-gray-200 border-b-2 border-white-500 mx-1.5 sm:mx-6'
              : 'border-transparent hover:text-gray-800 dark:hover:text-gray-200 hover:border-blue-500',
            'transition-colors duration-300 transform mx-1.5 sm:mx-6',
          ]"
           href="/">
          Home
        </a>

        <a :class="[
            isActive('/about')
              ? 'text-gray-800 transition-colors duration-300 transform dark:text-gray-200 border-b-2 border-white-500 mx-1.5 sm:mx-6'
              : 'border-transparent hover:text-gray-800 dark:hover:text-gray-200 hover:border-blue-500',
            'transition-colors duration-300 transform mx-1.5 sm:mx-6',
          ]"
           href="/about">
          About Us
        </a>

        <a :class="[
            isActive('/products')
              ? 'text-gray-800 transition-colors duration-300 transform dark:text-gray-200 border-b-2 border-white-500 mx-1.5 sm:mx-6'
              : 'border-transparent hover:text-gray-800 dark:hover:text-gray-200 hover:border-blue-500',
            'transition-colors duration-300 transform mx-1.5 sm:mx-6',
          ]"
           href="/products">
          Products
        </a>

        <a :class="[
            isActive('/store')
              ? 'text-gray-800 transition-colors duration-300 transform dark:text-gray-200 border-b-2 border-white-500 mx-1.5 sm:mx-6'
              : 'border-transparent hover:text-gray-800 dark:hover:text-gray-200 hover:border-blue-500',
            'transition-colors duration-300 transform mx-1.5 sm:mx-6',
          ]"
           href="/store">
          Online Store
        </a>

        <a :class="[
            isActive('/contact')
              ? 'text-gray-800 transition-colors duration-300 transform dark:text-gray-200 border-b-2 border-white-500 mx-1.5 sm:mx-6'
              : 'border-transparent hover:text-gray-800 dark:hover:text-gray-200 hover:border-blue-500',
            'transition-colors duration-300 transform mx-1.5 sm:mx-6',
          ]"
           href="/contact">
          Contact Us
        </a>
      </div>
    </nav>
  </header>
</template>

<script setup>
import { ref, computed } from "vue";
import { useRoute } from "vue-router";

const route = useRoute();

const isActive = (path) => {
  return route.path === path;
};
</script>

<style scoped>
/* 添加一些基本样式 */
.navbar {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  /* 其他样式 */
}
</style>
