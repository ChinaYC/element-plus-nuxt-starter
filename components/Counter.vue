<script setup lang="ts">
const { count } = useCount();
  //1
</script>

<template>
  <el-input-number v-model="count" :min="1" :max="10" />
</template>
