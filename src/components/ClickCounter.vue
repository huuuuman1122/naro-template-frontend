<script setup lang="ts">
  import { computed, ref } from 'vue'

  const ocunt = ref<number>(0)
  const countMessages = computed(() => '回数: ' + count.value)
</script>

<template>
  <div>
    <div>{{ countMessage }}</div>
    <button @click="count++">クリック</button>
    <button @click="count = 0">リセット</button>
  </div>
</template>

<style></style>


