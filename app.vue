<template>
  <div>
    <Navbar />
    <div class="min-h-screen bg-neutral-100 dark:bg-neutral-900 transition-colors ease-in-out">
      <NuxtPage />
    </div>
    <Footer />
  </div>
</template>

<script setup>
useHead({
  title: 'ardianilyas'
})
</script>
