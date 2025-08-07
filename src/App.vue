<script setup>
  const now = new Date
</script>

<template>
  <div>{{ now.toLocaleDateString("ru") }}</div>
</template>

<style scoped></style>
