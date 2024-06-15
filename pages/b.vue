<script setup>
defineOptions({
  name: 'bpage',
});
</script>

<template>
  <div :is="activeComponent">
  B Page: Use this input for test keep alive
  <KeepAlive>
    <input :is="activeComponent" />
  </KeepAlive>
  <button @click="$router.go(-1)">Go Back</button>
  </div>
  
</template>
