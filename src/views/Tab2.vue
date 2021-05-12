<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Tab 2</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Tab 2</ion-title>
        </ion-toolbar>
      </ion-header>
                      <!-- Default textarea -->
                  <ion-textarea></ion-textarea>

                  <!-- Textarea in an item with a placeholder -->
                  <ion-item>
                    <ion-textarea placeholder="Enter more information here..."></ion-textarea>
                  </ion-item>

                  <!-- Textarea in an item with a floating label -->
                  <ion-item>
                    <ion-label position="floating">Description</ion-label>
                    <ion-textarea></ion-textarea>
                  </ion-item>

                  <!-- Disabled and readonly textarea in an item with a stacked label -->
                  <ion-item>
                    <ion-label position="stacked">Summary</ion-label>
                    <ion-textarea
                      disabled
                      readonly
                      value="Ionic enables developers to build performant, high-quality mobile apps.">
                    </ion-textarea>
                  </ion-item>

                  <!-- Textarea that clears the value on edit -->
                  <ion-item>
                    <ion-label>Comment</ion-label>
                    <ion-textarea clear-on-edit="true"></ion-textarea>
                  </ion-item>

                  <!-- Textarea with custom number of rows and cols -->
                  <ion-item>
                    <ion-label>Notes</ion-label>
                    <ion-textarea rows="6" cols="20" placeholder="Enter any notes here..."></ion-textarea>
                  </ion-item>
      
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent, IonTextarea, IonLabel, IonItem } from '@ionic/vue';

export default  {
  name: 'Tab2',
  components: { IonHeader, IonToolbar, IonTitle, IonContent, IonPage, IonTextarea, IonLabel, IonItem }
}
</script>