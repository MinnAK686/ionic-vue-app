<template>
    <ion-page>
        <ion-tabs>
            <ion-router-outlet></ion-router-outlet>
            <ion-tab-bar slot="bottom">
                <ion-tab-button tab="tab1" href="/tabs/tab1" class="dynIcon">
                    <ion-icon :icon="homeOutline" />
                    <!-- <ion-icon selected:icon="home" /> -->
                </ion-tab-button>

                <ion-tab-button tab="tab2" href="/tabs/tab2" class="dynIcon">
                    <ion-icon :icon="search" />
                </ion-tab-button>

                <ion-tab-button tab="tab3" href="/tabs/tab3" class="dynIcon">
                    <ion-icon :icon="micOutline" />
                </ion-tab-button>

                <ion-tab-button tab="tab4" href="/tabs/tab4" class="dynIcon">
                    <ion-icon :icon="notificationsOutline" />
                </ion-tab-button>

                <ion-tab-button tab="tab5" href="/tabs/tab5" class="dynIcon">
                    <ion-icon :icon="mailOutline" />
                </ion-tab-button>
            </ion-tab-bar>
        </ion-tabs>
    </ion-page>
</template>

<script setup lang="ts">
import {
    IonTabBar,
    IonTabButton,
    IonTabs,
    IonLabel,
    IonIcon,
    IonPage,
    IonRouterOutlet,
} from "@ionic/vue";
import {
    home,
    homeOutline,
    search,
    searchSharp,
    mic,
    micOutline,
    notifications,
    notificationsOutline,
    mail,
    mailOutline,
} from "ionicons/icons";
</script>

<style>
.tab-selected.dynIcon {
    color: #000;
}
</style>
