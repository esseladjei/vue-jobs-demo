<script setup>
import Navbar from '@/components/Navbar.vue';
import { RouterView } from 'vue-router';
</script>

<template>
  <Navbar />
  <RouterView /> <!-- In your App.vue ,You inport RouterView and use it,Like outlet in React.js, this is where the view/page will show -->
</template>
