<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Home2</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content class="ion-padding">
      <ion-button router-link="/sobre">Ir para Sobre</ion-button>
    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent, IonButton } from '@ionic/vue'
</script>
