<template>
  <headers class=" w-full p-2 flex justify-between bg-white shadow-md fixed top-0 z-10">
    <img src="@/assets/logo.png" alt="icon" class=" w-14">
    <ul class=" w-1/2 flex justify-around mt-4">
      <li><headerBottun title="profile" /></li>
      <li><headerBottun title="skills" /></li>
      <li><headerBottun title="products" /></li>
      <li><headerBottun title="form" /></li>
    </ul>
  </headers>
</template>

<script setup>
import headerBottun from '@/components/parts/headerBottun';

</script>