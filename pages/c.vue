<script setup>
defineOptions({
  name: 'cpage',
});
</script>

<template>
  <div>
    C Page: Use this input for test keep alive
    <input />
    <button @click="$router.go(-1)">Go Back</button>
  </div>
</template>
