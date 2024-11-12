<script setup>
import Navbar from './components/Navbar.vue';

</script>

<template>
  <Navbar />
  <Hero title="Test Title" subtitle="Test Subtitle"/>
  <HomeCards />
  <JobListings :limit="3" :showButton="true"/>
</template>