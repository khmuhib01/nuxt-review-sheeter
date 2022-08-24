<template>
  <h1>{{ data }}</h1>
</template>

<script setup>
const { data } = await useFetch("/api/hello");
</script>

<style>
</style>