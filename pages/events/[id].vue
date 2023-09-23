<template>
  <div class="flex items-center justify-center">
    <h1 class="text-2xl font-bold">
        Dynamic id: {{ this.$route.params.id }}
    </h1>
  </div>
</template>
<script setup >
    // we can access the route with the useRoute method
    // const route = useRoute();
    // console.log(route.params.id);  

    // we can access current/runtime context of the application with useNuxtApp method 
    const nuxt = useNuxtApp();
    console.log(nuxt);      
</script>
