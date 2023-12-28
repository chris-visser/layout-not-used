<script setup lang="ts">
useHead({
  htmlAttrs: {
    'data-theme': 'clubs'
  }
})
</script>

<template>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>

<style lang="postcss">
.page-enter-active,
.page-leave-active {
  transition: all 0.1s;
}

.page-enter-from,
.page-leave-to {
  opacity: 0;
  filter: blur(0.7rem);
}

@media (prefers-reduced-motion) {
  .page-enter-active,
  .page-leave-active {
    transition: none !important;
  }

  .page-enter-from,
  .page-leave-to {
    opacity: 1;
    filter: none;
  }
}
</style>