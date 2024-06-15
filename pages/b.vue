<script setup>
defineOptions({
  name: 'bpage',
});
</script>

<template>
  B Page: Use this input for test keep alive
  <input />
  <button @click="$router.go(-1)">Go Back</button>
</template>
