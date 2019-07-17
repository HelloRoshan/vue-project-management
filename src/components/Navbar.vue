<template>
  <nav>
    <v-toolbar flat app class="grey darken-4">
      <v-toolbar-side-icon flat class="grey--text" @click="drawer = !drawer"></v-toolbar-side-icon>
      <v-toolbar-title class="text-uppercase grey--text">
        <span class="font-weight-light">Project </span>
        <span>Management</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn flat class="grey darken-4 grey--text">Login</v-btn>
      <v-btn color="grey lighten-2">
        <span>Sign Out</span>
      </v-btn>
    </v-toolbar>

    <v-navigation-drawer v-model="drawer" app class="blue-grey darken-4">
      <p>test</p>
    </v-navigation-drawer>
  </nav>
</template>
<script>
export default {
  data() {
    return {
      drawer: false,
    };
  },
};
</script>
