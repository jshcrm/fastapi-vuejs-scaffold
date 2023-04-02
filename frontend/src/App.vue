<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
import NavBar from "./components/NavBar.vue";
</script>

<template>
  <v-app>
    <NavBar></NavBar>

    <div class="mt-[20px]">
      <RouterView />
    </div>
  </v-app>
</template>

<style scoped></style>
