<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
import NavBar from "./components/NavBar.vue";
</script>

<template>
  <NavBar></NavBar>

  <div class="mt-[20px]">
    <RouterView />
  </div>
</template>

<style scoped></style>
