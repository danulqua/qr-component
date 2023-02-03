<template>
  <div class="flex h-full min-h-[500px] items-center justify-center space-y-4">
    <QrCode />
  </div>
</template>

<script setup>
import QrCode from "@/components/QrCode.vue";
</script>

<style>
html,
body,
#app {
  @apply h-full;
}

body {
  @apply bg-light-gray;
}
</style>
