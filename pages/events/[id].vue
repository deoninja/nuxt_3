<script setup>
    // const route = useRoute();
  // console.log(route.params.id);
  const nuxt = useNuxtApp();
  console.log(nuxt);
</script>

<template>
  <div>event id: {{  $route.params.id  }}</div>
</template>
