<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header class="text-black">
    <div class="max-w-7xl mx-auto px-6 flex items-center justify-between h-20">
      <!-- Logo -->
      <div class="flex items-center space-x-2">
        <img src="../public/trialog_logo.png" alt="Logo" class="h-12">
      </div>

      <!-- Navigation -->
      <nav class="flex items-center space-x-6">
        <RouterLink to="/" class="hover:text-gray-300">Home</RouterLink>
        <RouterLink to="/ueber-uns" class="hover:text-gray-300">Über uns</RouterLink>
        <RouterLink to="/kontakt" class=" px-5 py-3 bg-[#9a0404] rounded-xl text-white">Kontakt</RouterLink>
      </nav>
    </div>
  </header>


  <RouterView />
</template>
