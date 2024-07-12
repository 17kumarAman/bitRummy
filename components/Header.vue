<template>
  <div>
    <nav
      class="flex items-center justify-between mx-auto p-4 md:px-16 md:py-10"
    >
      <NuxtLink to="/" class="flex items-center">
        <img
          src="http://bityrummy.in/wp-content/uploads/2023/11/Screenshot_2023-11-08_101012-removebg-preview.png"
          alt="Logo"
          class="h-16"
        />
      </NuxtLink>
      <div class="hidden md:flex text-xl">
        <ul class="flex gap-x-7 text-white">
          <NuxtLink to="/" class="hover:text-yellow-500">Home</NuxtLink>
          <NuxtLink to="/about" class="hover:text-yellow-500">About</NuxtLink>
          <NuxtLink to="/contact" class="hover:text-yellow-500">Contact</NuxtLink>
        </ul>
      </div>
      <div class="md:hidden">
        <button
          class="text-white focus:outline-none"
          @click="isMenuOpen = !isMenuOpen" 
        >
          <svg
            class="w-6 h-6"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M4 6h16M4 12h16m-7 6h7"
            ></path>
          </svg>
        </button>
      </div>
      <div class="hidden md:block">
        <a
          href="jayaganesha.apk"
          download="jayaganesha.apk"
          class="bg-yellow-600 text-white px-4 py-2 text-xl rounded hover:bg-yellow-700"
        >
          Download App
        </a>
      </div>
    </nav>
    <div v-if="isMenuOpen" class="md:hidden bg-gray-800 text-white p-4">
      <ul class="flex flex-col gap-y-4">
        <NuxtLink to="/" class="hover:text-yellow-500">Home</NuxtLink>
        <NuxtLink to="/about" class="hover:text-yellow-500">About</NuxtLink>
        <NuxtLink to="/" class="hover:text-yellow-500">Contact</NuxtLink>
        <li>
          <a
            class="bg-yellow-600 text-white px-6 py-2 rounded hover:bg-yellow-700 w-full"
            href="jayaganesha.apk"
            download="jayaganesha.apk"
          >
            Download App
          </a>
        </li>
      </ul>
    </div>
  </div>
</template>

<script setup>
import { ref } from "vue";

const isMenuOpen = ref(false);


</script>
