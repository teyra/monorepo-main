<template>
  <button><slot></slot></button>
</template>

<script setup lang="ts">
withDefaults(defineProps(), {
  type: 'primary',
});
</script>
