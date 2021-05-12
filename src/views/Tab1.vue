<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Moin</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Moin</ion-title>
        </ion-toolbar>
      </ion-header>
                      <ion-card>
                        <ion-card-header>
                          <ion-card-subtitle>Card Subtitle</ion-card-subtitle>
                          <ion-card-title>Card Title</ion-card-title>
                        </ion-card-header>

                        <ion-card-content>
                          Keep close to Nature's heart... and break clear away, once in awhile,
                          and climb a mountain or spend a week in the woods. Wash your spirit clean.
                        </ion-card-content>
                      </ion-card>

                      <ion-card>
                        <ion-item>
                          <ion-icon :icon="pin" slot="start"></ion-icon>
                          <ion-label>DiNo New Shit</ion-label>
                          <ion-button fill="outline" slot="end">View</ion-button>
                        </ion-item>

                        <ion-card-content>
                          This is content, without any paragraph or header tags,
                          within an ion-card-content element.
                        </ion-card-content>
                      </ion-card>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent, IonCard,IonCardContent, IonCardSubtitle, IonCardTitle, IonIcon, IonItem, IonLabel } from '@ionic/vue';

export default {
  name: 'Tab1',
  components: { IonHeader, IonToolbar, IonTitle, IonContent, IonPage, IonCard, IonCardContent, IonCardSubtitle, IonCardTitle, IonIcon, IonItem, IonLabel }
}
</script>