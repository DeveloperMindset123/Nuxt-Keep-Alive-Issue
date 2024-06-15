<script setup>
defineOptions({
  name: 'apage',
});

const input = ref('');
</script>

<template>
  <div>
    A Page: Use this input for test keep alive
    <input v-model="input" />
    <button @click="$router.go(-1)">Go Back</button>
  </div>
</template>
