<script setup>
import ToolTop from '@/components/toolbar/ToolTop.vue';
</script>

<template>
  <ToolTop class="top"/>
</template>

<style scoped>
.top {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  z-index: 100;
}
</style>