<template>
  <div>All blog posts list</div>
</template>

<script setup>
const result = await queryContent("/").find();
console.log(result);
</script>

<style lang="scss" scoped></style>
