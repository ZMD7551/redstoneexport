<template>
  <div>
    <v-app>
      <AppBar></AppBar>
      <router-view></router-view>
    </v-app>
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
