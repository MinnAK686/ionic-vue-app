<template>
    <ion-page>
        <ion-header>
            <TopToolbar />
        </ion-header>
        <ion-content :fullscreen="true">
            <ion-header collapse="condense">
                <ion-toolbar>
                    <ion-title size="large">Tab 4</ion-title>
                </ion-toolbar>
            </ion-header>

            <NotificationsTab />
        </ion-content>
    </ion-page>
</template>

<script setup lang="ts">
import {
    IonPage,
    IonHeader,
    IonToolbar,
    IonTitle,
    IonContent,
} from "@ionic/vue";
import TopToolbar from "@/components/TopToolbar.vue";
import NotificationsTab from "@/components/NotificationsTab.vue";
</script>
