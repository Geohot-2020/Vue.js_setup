<script setup>
import { RouterLink } from 'vue-router';
</script>

<template>
        <section class="text-center flex flex-col justify-center items-center h-96">
      <i class="fas fa-exclamation-triangle text-yellow-400 fa-4x mb-4"></i>
      <h1 class="text-6xl font-bold mb-4">404 Not Found</h1>
      <p class="text-xl mb-5">This page does not exist</p>
      <RouterLink
        to="/"
        class="pi"
        >Go Back</RouterLink
      >
    </section>

</template>