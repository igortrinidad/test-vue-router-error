<template>
  <main>
    <h1>Index</h1>
    <h3>{{ route.fullPath }}</h3>
  </main>
</template>

<script setup lang="ts">
import { useRoute } from 'vue-router';
const route = useRoute();
</script>
