<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div class="container mx-auto px-10">
  <header>
    <div>
      <nav class="flex gap-10 my-5">
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />

  </div>
</template>

<style scoped></style>
