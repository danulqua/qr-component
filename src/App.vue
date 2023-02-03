<template>
  <div class="flex h-full min-h-[500px] items-center justify-center space-y-4">
    <QrCode
      title="Improve your front-end skills by building projects"
      subtitle="Scan the QR code to visit Frontend Mentor and take your coding skills to
      the next level"
    />
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
