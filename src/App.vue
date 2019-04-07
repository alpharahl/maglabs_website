<template>
  <v-app>
    <Header/>
    <v-content>
      <TitleBar/>
    </v-content>
  </v-app>
</template>

<script>
import Header from './components/Header/Header';
import TitleBar from './components/TitleBar/TitleBar'

export default {
  name: 'App',
  components: {
    Header,
    TitleBar
  },
  data () {
    return {
      //
    }
  }
}
</script>
