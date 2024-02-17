<template>
  <div>
    <h2>{{ title }}</h2>
  </div>
</template>

<script setup lang="ts">
  const title = useState('title', () => 'Cant get shared state');
</script>

<style scoped></style>
