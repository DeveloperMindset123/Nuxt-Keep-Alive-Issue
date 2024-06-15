<script setup>
// define the name of the page here
defineOptions({
  name: 'dpage',
});
</script>

<template>
  D Page: Use this input for test keep alive
  <input />
  <button @click="$router.go(-1)">Go Back</button>
</template>
