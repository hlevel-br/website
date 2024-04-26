<template>
  <main class="HomeView">
    <Logo class="logo"/>
  </main>
</template>

<script setup>
import Logo from '@/components/Logo.vue';
</script>

<style>
.HomeView {
  display: flex;
  height: 100vh;
  justify-content: center;
  align-items: center;
}

.logo {
  height: 70vh;
}
</style>