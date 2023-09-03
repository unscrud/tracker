<script setup lang="ts">
import BarraLateral from './components/BarraLateral.vue'
import FormTask from './components/FormTask.vue'
</script>

<template>
  <main class="columns is-gapless is-multiline">
    <div class="column is-one-quarter">
      <BarraLateral />
    </div>
    <div class="column is-three-quarters">
      <FormTask />
    </div>
  </main>
</template>

<style scoped>
</style>
