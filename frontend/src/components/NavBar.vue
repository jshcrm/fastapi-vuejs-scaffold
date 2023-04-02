<script setup lang="ts"></script>

<template>
  <v-app-bar>
    <v-app-bar-nav-icon @click.stop="drawer = !drawer"></v-app-bar-nav-icon>
    <v-app-bar-title>AWS Deploy</v-app-bar-title>
  </v-app-bar>

  <v-navigation-drawer
    v-model="drawer"
    location="bottom"
    temporary
  >
    <v-list
      :items="items"
    ></v-list>
  </v-navigation-drawer>
</template>

<script lang="ts">
export default {
  data() {
    const data = {
      drawer: false,
      dropdownActive: false,
      items: [
        {title: "Foo", value: "Bar"}
      ],
    };
    return data;
  },
  computed: {},
  methods: {},
};
</script>
