<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-buttons slot="start">
          <ion-back-button :default-href="pageDefaultBackLink"></ion-back-button>
        </ion-buttons>
        <ion-title>
          <h1>{{ pageTitle }}</h1>
        </ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content>
      <slot />
    </ion-content>
  </ion-page>
</template>

<script>
import {
  IonPage,
  IonHeader,
  IonTitle,
  IonContent,
  IonToolbar,
  IonBackButton,
  IonButtons
} from "@ionic/vue";

export default {
    props: ['pageTitle'],
    components: {
    IonPage,
    IonHeader,
    IonTitle,
    IonContent,
    IonToolbar,
    IonBackButton,
    IonButtons
  },
}
</script>