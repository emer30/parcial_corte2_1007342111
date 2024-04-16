<template>
  
  <ion-page>
    <ion-toolbar>
  <ion-item>
<ion-title class="ion-text-center">REALIZA TU PEDIDO</ion-title>

</ion-item>

<ion-item>
      <ion-label position="floating">nombre</ion-label>
      <ion-input type="text" v-model="name"></ion-input>
    </ion-item>

    <ion-item>
      <ion-label position="floating">apellido</ion-label>
      <ion-input type="text" v-model="surname"></ion-input>
    </ion-item>
    <ion-item>
      <ion-label position="floating">telefono</ion-label>
      <ion-input type="text" v-model="phone"></ion-input>
    </ion-item>
    <ion-item>
      <ion-label position="floating">lista de tu pedido a realizar</ion-label>
      <ion-input type="text" v-model="food"></ion-input>
    </ion-item>
<ion-button>comprar</ion-button>


    </ion-toolbar>

  
</ion-page>
</template>

<script lang="ts">

import { IonInput, IonItem, IonList } from '@ionic/vue';
import { defineComponent } from 'vue';

export default defineComponent({
  components: { IonInput, IonItem, IonList },



  data() {
  return {
    name: '',
    surname: '',
    phone :'',
    food:''
  }
},
 

}
);


</script>