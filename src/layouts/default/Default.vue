<template>
  <v-app :style="{background: $vuetify.theme.themes.light.colors.primary}">
    <default-bar />

    <default-view />
  </v-app>
</template>

<script setup>
  import DefaultBar from './AppBar.vue'
  import DefaultView from './View.vue'
</script>
