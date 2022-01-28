
<template>
  <div id="app">
  <v-app id="inspire">
    <div class="pa-0" style="max-height:100vh;overflow:hidden;">
      <v-img src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
        height="200px" width="100vw"
      ></v-img>
    <v-card class="mx-auto elevation-5 text-center pa-5" max-width="350" style="border-radius:20px;position:relative;top:-150px;"
    >
      <v-card-subtitle class="title white--text pa-1">
        Iniciar
      </v-card-subtitle>
      <v-card-subtitle class="pa-1">
        Empleados<br/> Compras/Ventas
      </v-card-subtitle>
      <v-text-field hide-details color="red" label="Usuario"></v-text-field>
      <v-text-field color="red" label="contraseña" type="password"></v-text-field>
      <v-card-actions>  
        <v-btn color="red" dark block rounded >
          Iniciar
        </v-btn>
      </v-card-actions>
        <span class="mt-2 subtitle-2 primary--text" style="cursor:pointer">Olvide Contraseña</span>
    </v-card>
      <div class="text-center" style="position:relative;top:-140px">
        <p class="ma-0">- Buscanos -</p>
        <v-btn color="grey" rounded outlined class="ma-2" width="200"><v-icon left color="blue">mdi-facebook</v-icon>Facebook</v-btn><br/>        
        <v-btn color="grey" rounded outlined class="ma-2" width="200"><v-icon left color="red">mdi-google</v-icon>Google</v-btn>
         <!-- <p class="mt-3">У вас нет аккаунта? <span class="red--text" style="cursor:pointer">Регистрация</span></p> -->
     </div>
      </div>
  </v-app>
</div>
</template>
<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
    name: 'IndexPage',

})
</script>