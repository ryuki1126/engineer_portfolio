<template>
  <h2 class=" block text-5xl font-bold">{{ title}}</h2>
  <div class=" w-28 h-1 bg-teal-400 mx-auto"></div>
</template>

<script setup>
import { defineProps } from 'vue';

defineProps({title: String});
</script>