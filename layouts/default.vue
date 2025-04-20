<template>
  <div class="min-h-screen flex flex-col">
    <TheHeader />
    <BreakingNewsTicker />
    <main class="flex-grow bg-gray-100">
      <slot />
    </main>
    <TheFooter />
  </div>
</template>

<script setup>
// Layout script
</script>