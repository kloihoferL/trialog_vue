<script setup>
import Header from '../components/header.vue';
import Products from "@/components/products.vue";
</script>

<template>

<Header></Header>

  <div class=" columns-2 container mx-auto">
    <div class="">
      <img src="../assets/consento.jpg"
           alt="Meeting"
           class="w-full ">
    </div>
    <div>
      <h3>Über uns</h3>
      <p></p>
    </div>
  </div>

  <Products></Products>

</template>
