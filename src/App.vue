<script setup lang="ts">
import BasicLayout from '@/layouts/BasicLayout.vue'

import { test } from './api/testController';
// healthCheck().then((res) => {
//   console.log(res)
// })
test().then((res) => {
  console.log(res)
})
</script>

<template>
  <BasicLayout />
</template>

<style>
</style>
