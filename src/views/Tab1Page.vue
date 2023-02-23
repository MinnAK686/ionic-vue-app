<template>
    <ion-page>
        <ion-header>
            <TopToolbar />
        </ion-header>
        <ion-content :fullscreen="true">
            <ion-header collapse="condense">
                <ion-toolbar>
                    <ion-title size="large">Tab 1</ion-title>
                </ion-toolbar>
            </ion-header>

            <HomeTab />
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
import HomeTab from "@/components/HomeTab.vue";
</script>
