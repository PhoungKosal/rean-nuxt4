<script setup lang="ts">
import ThemeToggle from '~/components/ThemeToggle.vue';


</script>

<template>
  <div>
    <p>Some default layout content shared across all pages</p>
    <ThemeToggle />
    <slot />
  </div>
</template>
