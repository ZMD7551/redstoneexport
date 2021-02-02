<template>
  <v-footer
    dark
    padless
    height="auto"
  >
    <v-card
      flat
      tile
      width="100%"
      class="indigo lighten-1 white--text text-center"
    >
      <v-card-text class="white--text ma-0">
          <v-text>Follow us on Social Media<br></v-text>
        <v-btn
          v-for="icon in icons"
          :key="icon"
          class="mr-2 white--text"
          icon
        >
          <v-icon size="24px">
            {{ icon }}
          </v-icon>
        </v-btn>
      </v-card-text>

      <v-card-text class="white--text mt-n5">
          <v-text>Contact Us<br></v-text>
            <v-icon
            class="mr-1 ml-5"
            color="white">
            call
            </v-icon>: 
            <v-text class="mr-1">1234567890</v-text> | 
            <v-icon
            class="mr-1"
            color="white">
            email
            </v-icon>: 
            <v-text>johndoe@xyz.com</v-text>
            
      </v-card-text>

      <v-divider></v-divider>

      <v-card-text class="white--text">
        {{ new Date().getFullYear() }} — <strong>RedStone Exports</strong>
      </v-card-text>
    </v-card>
  </v-footer>
</template>

<script>
export default {
    data: () => ({
      icons: [
        'mdi-facebook',
        'mdi-twitter',
        'mdi-linkedin',
        'mdi-instagram',
      ],
    }),
}
</script>

<style>

</style>