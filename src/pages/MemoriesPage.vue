<template>
  <base-layout page-title="All Memories">
    <ion-list>
          <ion-item router-link="/memories/1">A trip to the mountains</ion-item>
          <ion-item router-link="/memories/2">Jetskying at Pagang island</ion-item>
          <ion-item router-link="/memories/3">Swimming in the clear blue swamp</ion-item>
      </ion-list>
  </base-layout>
</template>

<script>
import {
  IonList,
  IonItem
} from "@ionic/vue";
export default {
  components: {
    IonList,
    IonItem,
  },
};
</script>