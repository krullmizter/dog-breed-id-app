<template>
  <ion-page>
    <ion-header :translucent="true">
      <ion-toolbar>
        <ion-title>Dog Breed Identification</ion-title>
      </ion-toolbar>
    </ion-header>

    <ion-fab>
      <ion-fab-button>
        <ion-icon :icon="camera"></ion-icon>
      </ion-fab-button>
    </ion-fab>
  </ion-page>
</template>

<script setup lang="ts">
  import { 
    IonContent, 
    IonHeader, 
    IonPage, 
    IonTitle, 
    IonToolbar,
    IonIcon,
    IonFab,
    IonFabButton
  } from '@ionic/vue';
  import { camera } from 'ionicons/icons';
</script>

<style scoped></style>
