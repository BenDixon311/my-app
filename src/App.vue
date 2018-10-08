<template>
  
 <v-layout row>
      <v-flex xs12 sm6 offset-sm3>
        <v-card>

  <app-header></app-header>
  

  <app-servers></app-servers>


  
  <app-server-details></app-server-details>
 <app-footer></app-footer>




  
  


        </v-card>
      </v-flex>



     </v-layout>

  
  
</template>

<script>
import Header from './Header.vue';
import Footer from './Footer.vue';
import Servers from './Servers.vue';
import ServerDetails from './ServerDetails.vue'

export default {

  components: {
    'app-header': Header,
    'app-servers': Servers,
    'app-server-details': ServerDetails,
    'app-footer': Footer
  },


}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
