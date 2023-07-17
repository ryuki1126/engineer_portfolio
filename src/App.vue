<template>
  <theHeader />
  <div class=" container mx-auto mt-20">
    <div class="py-8 h-screen">
      <h1 class=" text-5xl font-bold">Ryuki's Portfolio</h1>
    </div>
    <theProfile />
    <theSkills />
    <theProducts />
    <theForm />
  </div>
  <theFooter />
</template>

<script setup>
import theHeader from '@/components/theHeader';
import theProfile from './components/theProfile';
import theSkills from '@/components/theSkills';
import theProducts from '@/components/theProducts';
import theForm from '@/components/theForm';
import theFooter from '@/components/theFooter';

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
