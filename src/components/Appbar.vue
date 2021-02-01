<template>
  <div>
    <v-toolbar flat app>
      <div class="d-flex align-center">
        <v-img
          src="../assets/logo.jpg"
          class="shrink mr-2"
          contain
          width="50"
          @click.native="$router.push('/')"
        />
      </div>
      <v-btn flat @click.native="$router.push('about')">About</v-btn>
      <v-btn flat @click.native="$router.push('categories')">Categories</v-btn>
    </v-toolbar>
    <v-divider></v-divider>
  </div>
</template>