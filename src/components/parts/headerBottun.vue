<template>
  <div @click="scrollToElementId(title)" class="  px-4 py-2 text-lg font-bold cursor-pointer rounded-md hover:bg-teal-500 hover:bg-opacity-80 hover:text-white transition">
    {{ title }}
  </div>
</template>

<script setup>
import { defineProps } from 'vue';

defineProps({title: String});

const scrollToElementId = (title) => {
  const element = document.getElementById(title);
  element.style.scrollMarginTop = '6rem';
  element.scrollIntoView({ behavior: 'smooth' }); 
}

</script>