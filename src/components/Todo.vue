<template>
  <li>
    {{ title }}
    <button @click="$emit('remove')">Remove</button>
  </li>
</template>
<script>
export default {
  name: 'Todo',
  props: ['title'],
  emits: ['remove']
}
</script>
<style scoped>
</style>
