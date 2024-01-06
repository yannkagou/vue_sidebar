<template>
  <div class="app">
    <Sidebar />
    <RouterView />
  </div>
</template>

<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Sidebar from './components/Sidebar.vue';

</script>

<style scoped lang="scss">
.app {
  display: flex;

  main {
    flex: 1 1 0;
    padding: 2rem;

    @media (max-width: 768px) {
      padding-left: 6rem;
    }
  }
}

</style>
