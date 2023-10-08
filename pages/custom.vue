<template>
  <div class="container">
    <h1 class="text-3xl font-bold underline">Custom pages here ...!!!</h1>
    <!-- accessing img from assets folder -->
    <!-- <img class="w-full h-full" src="@/assets/2.png" alt="Discover Nuxt 3" /> -->
    <!-- accessing img from pubic folder -->
    <img class="w-full h-full" src="/2.png" alt="Discover Nuxt 3" />
  </div>
</template>
<script setup>
definePageMeta({
  layout: "custom",
});
</script>