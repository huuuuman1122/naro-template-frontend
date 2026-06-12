<script setup lang="ts">
import WelcomeMessage from './components/WelcomeMessage.vue'
import ClickCounter from './components/ClickCounter.vue'
</script>

<template>
  <main>
    <WelcomeMessage msg="Webエンジニアになろう講習会へようこそ" />
    <ClickCounter />
  </main>
</template>

<style scoped>
main {
  padding: 2rem;
}
</style>
