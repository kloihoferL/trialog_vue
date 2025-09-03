<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header class="text-black sticky">
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
  <footer class="footer sm:footer-horizontal bg-[#212121] text-base-content p-20 text-white">
    <aside>
      <img src="../public/logo.jpg" alt="Logo" class="h-12 mb-4">
      <p>
        TRIALOG Informatik GmbH
        <br />
        Ihr verlässlicher Partner seit 2003
      </p>
    </aside>
    <nav>
      <h6 class="footer-title">Produkte</h6>
      <a class="link link-hover">Branding</a>
      <a class="link link-hover">Design</a>
      <a class="link link-hover">Marketing</a>
      <a class="link link-hover">Advertisement</a>
    </nav>
    <nav>
      <h6 class="footer-title">Über Trialog</h6>
      <a class="link link-hover">About us</a>
      <a class="link link-hover">Contact</a>
      <a class="link link-hover">Jobs</a>
      <a class="link link-hover">Press kit</a>
    </nav>
    <nav>
      <h6 class="footer-title">Rechtliches</h6>
      <a class="link link-hover">Terms of use</a>
      <a class="link link-hover">Privacy policy</a>
      <a class="link link-hover">Cookie policy</a>
    </nav>
  </footer>

</template>
