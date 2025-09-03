<script setup>

</script>

<template>
  <section class="relative bg-gray-900 text-white z-30">
    <div class="absolute inset-0">
      <img src="../assets/header.jpg"
           alt="Meeting"
           class="w-full h-full object-cover opacity-70">
    </div>

    <!-- Overlay Content -->
    <div class="relative max-w-6xl mx-auto px-6 py-32">
      <p class="uppercase tracking-wide text-sm pt-10">TRIALOG INFORMATIK Gmbh</p>
      <h1 class="text-6xl md:text-5xl font-extrabold leading-tight mt-4">
        Ihr kompetenter Partner <br> rund ums Thema EDV
      </h1>
      <p class="text-xl mt-4 max-w-xl text-gray-200">
        Seit 2003 bieten wir zuverlässige IT-Lösungen und Erfahrung, auf die Sie zählen können.
      </p>
      <button class="mt-6 bg-[#9a0404] hover:bg-red-700 text-white font-semibold px-6 py-3 rounded-full shadow-lg transition mb-30">
        Kontaktieren Sie uns
      </button>
    </div>
  </section>

  <!-- Rote Kästchen -->
  <section class="bg-white boxes mb-30">
    <div class="max-w-6xl mx-auto grid grid-cols-1 md:grid-cols-3 gap-6 px-6">
      <div class="bg-[#9a0404] opacity-90 text-white p-15 shadow-lg text-center rounded-xl z-40 ">
        <div class="text-4xl mb-4">💼</div>
        <h3 class="text-xl font-bold mb-2">Netzwerktechnik</h3>
        <p class="text-sm text-red-100">
          Now is the time for us to push on and own this incredible movement.
        </p>
      </div>

      <div class="bg-[#9a0404] opacity-90 text-white p-15 shadow-lg text-center rounded-xl  z-40 ">
        <div class="text-4xl mb-4">⚕️</div>
        <h3 class="text-xl font-bold mb-2">IT Service</h3>
        <p class="text-sm text-red-100">
          Now is the time for us to push on and own this incredible movement.
        </p>
      </div>

      <div class="bg-[#9a0404] opacity-90 text-white p-15  shadow-lg text-center rounded-xl z-40 ">
        <div class="text-4xl mb-4">📜</div>
        <h3 class="text-xl font-bold mb-2">3 Produkt</h3>
        <p class="text-sm text-red-100">
          Now is the time for us to push on and own this incredible movement.
        </p>
      </div>

    </div>
  </section>

</template>

<style scoped>

</style>