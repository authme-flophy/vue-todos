<template>
  <header>
    <nav class="container">
      <div class="branding">
        <img src="../assets/Vue_Logo_Black.png" alt="vue black logo">
        <h1>Vue Todos</h1>
      </div>
      <ul class="nav-routes">
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </ul>
    </nav>
  </header>
</template>

<script setup>
import { RouterLink } from 'vue-router';
</script>

<style lang="scss" scoped>

</style>