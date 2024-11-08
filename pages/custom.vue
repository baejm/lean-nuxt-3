<template>
  <div>
    <NuxtLayout name="custom">
      <nuxtPage />
    </NuxtLayout>
  </div>
</template>

<script setup lang="ts">
definePageMeta({
  layout: false,
  layoutTransition: false,
});
</script>

<style scoped></style>
