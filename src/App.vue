<template>
  <div>
    <v-app>
      <AppBar/>
      <router-view></router-view>
      <Footer/>
    </v-app>
  </div>
</template>

<script>
import AppBar from "./components/Appbar";
import Footer from "./views/Footer.vue";
export default {
  name: "App",

  components: {
    AppBar,
    Footer
  },

  data: () => ({}),
};
</script>
