<template>
  <v-app>
    <AppBar title="About" />
    <v-main>
      <p>This is About!!</p>
    </v-main>
  </v-app>
</template>

<script>
import AppBar from '../components/AppBar.vue'

export default {
  name: 'About',
  components: {
    AppBar
  }
}
</script>
