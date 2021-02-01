<template>
  <div>
    <v-app>
      <v-main>
        <AppBar />
      </v-main>
    </v-app>
    <router-view />
  </div>
</template>

<script>
import AppBar from "./components/Appbar";
export default {
  name: "App",

  components: {
    AppBar,
  },

  data: () => ({
    //
  }),
};
</script>
