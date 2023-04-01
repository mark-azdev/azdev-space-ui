<template>
  <v-app>
    <default-bar />

    <default-view />

    <v-bottom-navigation>
      <v-btn value="Home" :to="{ name: 'Home' }">
        <v-icon>mdi-home</v-icon>
        Home
      </v-btn>

      <v-btn value="Bio" :to="{ name: 'Bio' }">
        <v-icon>mdi-book</v-icon>
        Bio
      </v-btn>
    </v-bottom-navigation>
  </v-app>
</template>

<script setup>
import DefaultBar from './AppBar.vue'
import DefaultView from './View.vue'
</script>
