<script setup lang="ts">
import HomeScreen from './components/layout/HomeScreen.vue'
import LoginScreen from './components/layout/LoginScreen.vue'
</script>

<template>
  <div class="w-full h-screen bg-black/10">
    <LoginScreen v-if="true" />
    <HomeScreen v-else/>

    <div>
      <p>Welcome to the Recipe Sharing App</p>
    </div>
  </div>
</template>

<style scoped></style>
