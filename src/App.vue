<script setup lang="ts">
import WelcomeMessage from './components/WelcomeMessage.vue'
import ItemList from './components/ItemList.vue'
</script>

<template>
  <main>
    <WelcomeMessage msg="Webエンジニアになろう講習会へようこそ" />
    <ItemList />
  </main>
</template>

<style scoped>
main {
  padding: 2rem;
}
</style>
