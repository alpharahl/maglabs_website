<template>
  <v-flex xs12>
    <v-card dark color="primary">
      <v-img :src="images.titleLogo"></v-img>
      <v-card-text class="px-0">12</v-card-text>
    </v-card>
  </v-flex>
</template>

<script>
  export default {
    name: "TitleBar",

    data () {
      return {
        images: {
          titleLogo: require('../../assets/Labs_Generic_Logo_White.png')
        }
      }
    }
  }
</script>

<style scoped>

</style>