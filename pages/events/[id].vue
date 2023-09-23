<template>
  <div class="flex items-center justify-center">
    <h1 class="text-2xl font-bold">
        Dynamic id: {{ this.$route.params.id }}
    </h1>
  </div>
</template>
<script setup>
    const route = useRoute();
    console.log(route.params.id);    
</script>
