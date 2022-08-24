<script setup>
import { RouterLink, RouterView } from 'vue-router';
</script>

<template>
  <header>
    <div class="wrapper">
      <h1>Revan Kurniawan</h1>
      <nav>
        <RouterLink onclick="linkActive()" to="/">Home</RouterLink>
        <RouterLink onclick="linkActive()" to="/about">About</RouterLink>
        <RouterLink onclick="linkActive()" to="/projects">Projects</RouterLink>
        <RouterLink onclick="linkActive()" to="/contact">Contact</RouterLink>
      </nav>
    </div>
  </header>
  <main>
    <RouterView />
  </main>
</template>