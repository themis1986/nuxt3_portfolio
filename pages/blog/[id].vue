<template>
  <div>We are inside blog</div>
  <div class="">Post id is {{ route.params.id }}</div>
</template>

<script setup>
const route = useRoute();
</script>

<style lang="scss" scoped></style>
