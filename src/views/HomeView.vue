<script setup>
  import { ref } from "vue"
  const today = new Date();
  const date = ref(today.getFullYear()+'-'+(today.getMonth()+1)+'-'+today.getDate());
</script>

<template>
  <main>
    <h1>Home page {{date}}</h1>
  </main>
</template>
