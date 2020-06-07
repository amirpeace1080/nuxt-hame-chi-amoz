<template>
  <v-app>
      <Header />
    
  
      <v-content class="theme--light grey lighten-4">
        <nuxt />
      </v-content>
    

      <Footer class="bg-white" />

  </v-app>
</template>

<script>
import Header from './../components/Header'
import Footer from './../components/Footer'

export default {
  components:{
    Header,
    Footer
  }
}
</script>

