<script setup>
import { RouterLink } from 'vue-router';
</script>

<template>
  <div class="hero bg-base-200 min-h-screen">
  <div class="hero-content text-center">
    <div class="max-w-md">
      <h1 class="text-5xl font-bold">Cheyenne's Portfolio</h1>
      <p class="py-6">
        Here's my stuff
      </p>
      <RouterLink to="/contact">
        <button class="btn btn-primary">Contact Me</button>
      </RouterLink>
    </div>
  </div>
</div>
</template>

<style scoped>
</style>
