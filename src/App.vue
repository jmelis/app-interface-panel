<template>
  <v-app>
    <v-navigation-drawer permanent clipped absolute overflow app></v-navigation-drawer>
    <v-toolbar clipped-left app absolute>
      <v-toolbar-title>App-Interface</v-toolbar-title>
    </v-toolbar>
    <v-content></v-content>
  </v-app>
</template>

<script>
export default {
  name: 'App',
  components: {
  },
  data () {
    return {
    }
  }
}
</script>
