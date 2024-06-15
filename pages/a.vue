<script setup>
defineOptions({
  name: 'apage',
});

const input = ref('');
</script>

<template>
  <div :is="activeComponent">
    A Page: Use this input for test keep alive
    <KeepAlive>
      <input :is="activeComponent" v-model="input" />
    </KeepAlive>
    <button @click="$router.go(-1)">Go Back</button>
  </div>
</template>
