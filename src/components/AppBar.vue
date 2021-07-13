<template>
  <v-app-bar absolute color="deep-purple accent-4" app>
    <v-toolbar-title class="white--text">{{ `${title}` }}</v-toolbar-title>
    <v-spacer></v-spacer>
    <router-link class="white--text" to="/">Home</router-link>
    <span class="white--text mx-2">|</span>
    <router-link class="white--text" to="/about">About</router-link>
  </v-app-bar>
</template>
<script>
export default {
  name: 'AppBar',
  props: {
    title: String
  }
}
</script>
